 <template>
  <div class="w-1/4">
    
    <h1 class="text-4xl font-normal text-[#E72B6F]">Benvenuto/a</h1>
    <span class="text-4xl font-bold text-[#E72B6F]">Michela</span>
    <div class="flex flex-col w-80 mt-10 table-border-collapse border-2 rounded-xl">
      <table>
        <tbody class="translate-x-9">
          
          <tr v-for="(tab, index) in tabs" :key="index" :class="{ 'rounded-t-lg': index === 0 }">
            <td
              class="px-6 py-4 font-normal text-xl "
              :class="{ 'border-t': index !== 0, 'border-b': index !== tabs.length - 1 }"
            >
              <router-link :to="tab.url" :class="{ 'text-[#E72B6F] font-semibold': isActiveTab(tab.url) }">{{ tab.name }}</router-link>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { useRoute } from 'vue-router';

export default defineComponent({
  data() {
    return {
      tabs: [
        { name: 'La tua Card', url: '/page2' },
        { name: 'I tuoi dati', url: '/page10' },
        { name: 'I tuoi Badge', url: '/page8' },
        { name: 'I tuoi Coupon', url: '/i-tuoi-coupon' },
        { name: 'Invita un amico', url: '/page9' },
        { name: 'Offerte esclusive', url: '/page4' },
        { name: 'Storico acquisti', url: '/storico-acquisti' },
        { name: 'FAQ', url: '/faq' },
        { name: 'Gestione ordini online', url: '/gestione-ordini-online' }
      ]
    };
  },
  methods: {
    isActiveTab(url: string) {
      const route = useRoute();
      return route.path === url;
    }
    
  }
});
</script>

<style scoped>
.rounded-t-lg {
  border-top-left-radius: 20%;
  border-top-right-radius: 20%;
}
</style> 


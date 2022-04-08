<template>
  <div class="Faq">
      <div class="py-5 my-5 bg-body rounded" style="max-width: 1200px; margin:30px auto">
          <h2 class="mb-2 mt-5"><strong>FAQ Page</strong></h2>
          <div class="row text-start">
              <div class="col-4 m-0">
                  <div class="faq1 faqQS" :class="{'active' : faqQS == 'faq1'}" @click="faqQs = 'faq1'"><h4>How can I use my land? Can I visit my land or explore it in some way?</h4></div>
                  <div class="faq2 faqQS" @click="faqQs = 'faq2'"><h4>When I buy the NFT, am I buying the actual land or am I financing protection of the forest?</h4></div>
                  <div class="faq3 faqQS" @click="faqQs = 'faq3'"><h4>How much land or what area does each NFT represent?</h4></div>
                  <div class="faq4 faqQS" @click="faqQs = 'faq4'"><h4>How do I know that the land I buy will be protected from fire, invasions etc?</h4></div>
                  <div class="faq5 faqQS" @click="faqQs = 'faq5'"><h4>How do I know the property is funded for what it needs?</h4></div>
              </div>
              <div class="col-8 faqAns" v-show="faqQs == 'faq1'">
                  <h3>How can I use my land? Can I visit my land or explore it in some way?</h3>
                  <p>You are buying the actual land with a firm commitment of preservation. This is NOT a financing vehicle or a game card for conservation of the forest (“buy this piece of art and the money will go to preservation”).</p>
                  <p>Of course, as more people buy these NFTs and corresponding forest areas with the intent to preserve, more and more people will participate for Malaysia rainforest conservation.</p>
              </div>
              <div class="col-8 faqAns" v-show="faqQs == 'faq2'">
                  <h3>How can I use my land? Can I visit my land or explore it in some way?</h3>
                  <p>You are buying the actual land with a firm commitment of preservation. This is NOT a financing vehicle or a game card for conservation of the forest (“buy this piece of art and the money will go to preservation”).</p>
                  <p>Of course, as more people buy these NFTs and corresponding forest areas with the intent to preserve, more and more people will participate for Malaysia rainforest conservation.</p>
              </div>
              <div class="col-8 faqAns" v-show="faqQs == 'faq3'">
                  <h3>How can I use my land? Can I visit my land or explore it in some way?</h3>
                  <p>You are buying the actual land with a firm commitment of preservation. This is NOT a financing vehicle or a game card for conservation of the forest (“buy this piece of art and the money will go to preservation”).</p>
                  <p>Of course, as more people buy these NFTs and corresponding forest areas with the intent to preserve, more and more people will participate for Malaysia rainforest conservation.</p>
              </div>
              <div class="col-8 faqAns" v-show="faqQs == 'faq4'">
                  <h3>How can I use my land? Can I visit my land or explore it in some way?</h3>
                  <p>You are buying the actual land with a firm commitment of preservation. This is NOT a financing vehicle or a game card for conservation of the forest (“buy this piece of art and the money will go to preservation”).</p>
                  <p>Of course, as more people buy these NFTs and corresponding forest areas with the intent to preserve, more and more people will participate for Malaysia rainforest conservation.</p>
              </div>
              <div class="col-8 faqAns" v-show="faqQs == 'faq5'">
                  <h3>How do I know the property is funded for what it needs?</h3>
                  <p>You are buying the actual land with a firm commitment of preservation. This is NOT a financing vehicle or a game card for conservation of the forest (“buy this piece of art and the money will go to preservation”).</p>
                  <p>Of course, as more people buy these NFTs and corresponding forest areas with the intent to preserve, more and more people will participate for Malaysia rainforest conservation.</p>
              </div>
          </div>
      </div>
</div>
</template>

<script>
export default {
    data() {
      return {
        faqQs: 'faq1',
        // isActive: false,
      }
    },

    methods:{

    }

}
</script>

<style>

.faqQS {
    cursor: pointer;
    /* border-style: solid; */
    padding: 5%;
}

.faqQS:hover {
    cursor: pointer;
    background-color: rgb(4, 139, 47);
}

.faqAns{
    /* border-style: solid; */
    padding: 1.1% 2%;
}
</style>
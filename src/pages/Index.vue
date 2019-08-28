<template>
<Layout>
<div class="span-17 colborder" id="content">
      <h1 class="loud">Vue Wordpress Blueprint CSS</h1>
      <p>
        <img class="right" src="../assets/img/coins.png" width="280px" alt="Bounty" />
        Vue Wordpress with Blueprint CSS. 
      </p>
 
 
      <p>
        .           
      </p>
 
      <hr />
      <div class="span-8 colborder">
        <h4 class="prepend-5">Upload something</h4>
        <p>
          To paraphrase Nike - Just build stuff! 
        </p>      
      </div>
 
      <div class="span-8 last">
        <h4 class="prepend-5">Write a Review</h4>
        <p>
          Your thoughts on Vue Wordpress Blueprint are welcome! 
        </p>      
      </div>
    </div>
 
    <div class="span-6 last" id="sidebar">
 
      <div id="recent-books">
        <h3 class="caps">Read something</h3>
 
        <div class="box">
         <a href="#" class="quiet">More stuff</a></a>
          <div class="quiet">Nov. 29, 2008</div>
          <div class="quiet">by Craven</div>
        </div>
 
      </div>
 
      <div class="prepend-top" id="recent-reviews">
        <h3 class="caps">Recent Reviews</h3>
        <div class="box">
          <span class="quiet">Thor reviewed Viue Wordpress</span>
          <div class="quiet">Rating: 4/5</div>
           <a href="#" class="quiet">Read review</a>
        </div>
 
      </div>
    </div>
</Layout>
</template>
<script>
export default {
      head () {
        return {
          title: `Gridsome Vue Wordpress`,
          metaInfo: [
            {
              hid: 'description',
              name: 'description',
              content: 'Gridsome Vue - A front-end wordpress SEO friendly in vue.js'
            },
            {
              property: 'og:title',
              content: 'Gridsome Vue'
            },
            {
              property: 'og:description',
              content: 'Gridsome Vue - A front-end wordpress SEO friendly in vue.js'
            },
            {
              property: 'og:type',
              content: 'post'
            },
            {
              name: 'twitter:title',
              content: 'Gridsome Vue'
            },
            {
              name: 'twitter:description',
              content: 'Gridsome Vue - A front-end wordpress SEO friendly in vue.js'
            }
          ]
        }
      }
    }
</script>
<style>
.container {
width:90%;
}
</style>

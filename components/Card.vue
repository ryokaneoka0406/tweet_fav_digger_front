<template>
  <div class="mb-2">
    <client-only>
      <link-prevue :url="url">
        <template slot-scope="props">
          <div class="card">
            <div class="card-body">
              <div style="width: 8rem; height: 8rem" class="float-left mr-1">
                <img
                  :src="props.img"
                  alt=""
                  style="
                    width: 6rem;
                    height: 6rem;
                    margin: 1rem;
                    object-fit: contain;
                  "
                />
              </div>
              <div>
                <div v-if="props.title">
                  <a :href="props.url">
                    <p v-if="props.title.length < 30" class="card-title">
                      {{ props.title }}
                    </p>
                    <p v-else class="card-title text-truncate">
                      {{ props.title }}
                    </p>
                  </a>
                </div>
                <div v-else>
                  <a :href="props.url">
                    <p class="card-title text-muted">no title</p>
                  </a>
                </div>

                <p v-if="props.description" class="text-truncate">
                  {{ props.description }}
                </p>
                <p v-else class="text-muted">
                  (no description in this article)
                </p>
              </div>
            </div>
          </div>
        </template>
      </link-prevue>
    </client-only>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  props: {
    url: {
      type: String,
    },
  },
});
</script>

<style>
</style>

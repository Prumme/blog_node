<script>
  import { format, parseISO } from 'date-fns'
  import ButtonLink from './ButtonLink.svelte'

  export let post
</script>

<p class="text-sm h-min">
  <a href={`/posts/${post.slug}`}>{post.title}</a>
</p>

<style>
  a {
    text-decoration: none;
  }
</style>

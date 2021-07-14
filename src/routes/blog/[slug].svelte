<script context="module">
    export async function load({ page }) {

        const Post = (await import(`/src/posts/${page.params.slug}.md`)).default;

        return {
            props: {
                Post
            }
        }
    }
</script>

<script>
    export let Post;
</script>

<Post />

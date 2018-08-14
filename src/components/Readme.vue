<script>
import readme from "../../README.md"
import NpmOrYarn from "./NpmOrYarn.vue"

export default {
  extends: readme.vue.component,
  components: { NpmOrYarn }
}
</script>

<style scoped>
@import "../../node_modules/github-markdown-css/github-markdown.css";
</style>

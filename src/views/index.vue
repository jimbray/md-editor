<template>
  <codemirror-editor />
</template>

<script>
import CodemirrorEditor from './CodemirrorEditor'
import { inject } from '@vercel/analytics';

inject();


export default {
  name: `App`,
  components: {
    CodemirrorEditor,
  },
}
</script>

<style scoped></style>

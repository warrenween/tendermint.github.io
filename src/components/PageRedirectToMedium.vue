<template lang='pug'>
redirect(
  label='Redirecting you to Medium'
  url='https://blog.cosmos.network/tendermint/home'
)
</template>

<script>
import Redirect from './Redirect'
export default {
  name: 'page-redirect-to-medium',
  components: { Redirect }
}
</script>

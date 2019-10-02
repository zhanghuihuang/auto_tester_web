<template>
  <div class="header-bar">
    <AutoComplete
            v-model="current_env"
            :data="environments"
            placeholder="请选择环境"
            clearable
            style="width:200px">
    </AutoComplete>
    <Icon type="md-eye" class="custom-evn-btn"/>
    <Icon type="md-settings" class="custom-evn-btn"/>
    <div class="custom-content-con">
      <slot></slot>
    </div>
  </div>
</template>
<script>
import './header-bar.less'
export default {
  name: 'HeaderBar',
  components: {
  },
  props: {
    environments: Array,
    current_env: String
  },
  computed: {
  },
  methods: {
  }
}
</script>

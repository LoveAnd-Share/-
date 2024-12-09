<template>
     <a-button @click="info">提示</a-button>
</template>
<script>
import { message } from 'ant-design-vue';
export default {

    data () {
        return {
            tips: '提示'
        }
    },
    methods: {
        info() {
            messageApi.info('');
        }
        
    }
}
</script>
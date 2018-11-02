[github地址](https://github.com/davidroyer/vue2-editor)
[官方文档](https://www.vue2editor.com/)
npm安装：$ npm install --save vue2-editor
最简单的使用方式：

    <template>
        <div id="app">
            <vue-editor v-model="content"></vue-editor>
        </div>
    </template>
    
    <script>
    import { VueEditor } from 'vue2-editor'
    export default {
        components: {
            VueEditor
        },
        data() {
            return {
                content: ''
            }
        }
    }
    </script>

代码效果图：
![演示效果图](https://www.vue2editor.com/hero-home.png)

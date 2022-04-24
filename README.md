#### Chrome浏览器插件：
```
格式化json数据： JSON-handle
Github目录：     Octotree-Github code tree
    VPN免费：   Urban Free VPN 
图片批量下载：    Fatkun
谷歌翻墙：        谷歌上网助手@1.4.3
vue.js调试工具：  Vue.js devtools@6.1.4
```
#### VsCode插件安装
```
设置编辑器语言：  Chinese(Simplified)(简体中文)
以localhost打开单文件： Live Server
代码格式化：ESlint
vue单文件提示： Vetur
```
#### 软件
```
截图：Snipaste
编辑器：Vscode、sublime、Notepad
量尺寸：PxCook
视频：VLC media player
电脑全局搜索：Listary version 5.00
获取请求：Postman、charles、Fiddler
笔记： Evernote、印象笔记、Typora
```

#### vscode设置代码块
```
位置：文件—>首选项—>用户片段
{ 
	"Vue2—Props版本": { 
		"prefix": "temp2", 
		"body": [ 
		  "<template>", 
				"<div class=\"container\">主页</div>", 
		  "</template>\n", 
		  "<script>", 
		  "export default {", 
		  		"name:'Index',", 
    	  		"components:{},", 
    	   		"props:{},", 
		  		"  data() {", 
		  		"    return {}", 
		  		"  },", 
		  		"computed:{},", 
		  		"watch:{},", 
		  		"created() {},",                                
                                "mounted() {},",
		  		"methods: {}", 
		  	"}", 
		  "</script>\n", 
		  "<style scoped lang=\"less\">\n", 
		  "</style>", 
		  "$0" 
		], 
		"description": "Vue2—Props版本" 
	  } 
}
```
#### eslint需要在vscode中进行一些参数的配置：
```
位置：左下角设置图标—>设置—>右上角打开设置—>settings.json
{  
    "eslint.enable": true, 
    "eslint.run": "onType", 
    "eslint.options": { 
        "extensions": [ 
            ".js", 
            ".vue", 
            ".jsx", 
            ".tsx" 
        ] 
    }, 
    "editor.codeActionsOnSave": { 
        "source.fixAll.eslint": true 
    } 
}

配置二、
"vetur.format.defaultFormatterOptions": { 
        "prettier": { 
            "semi": false, 
            "singleQuote": true 
        }, 
        "wrap_attributes": "force-aligned" 
    }, 
    "javascript.format.insertSpaceBeforeFunctionParenthesis": true, 
    "vetur.format.defaultFormatter.js": "vscode-typescript", 
    "vetur.format.defaultFormatter.html": "js-beautify-html"
```

#### 在vscode中禁止显示node_modules目录
![Image text](https://github.com/xiaomarvin9527/document/blob/main/img/1.png)
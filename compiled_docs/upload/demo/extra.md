{"title":"额外内容","meta":{"title":"额外内容","description":"\n<p>提醒: <code>https://www.easy-mock.com/mock/5b713974309d0d7d107a74a3/alifd/upload</code>接口:</p>\n<blockquote>\n<ol>\n<li>该接口仅作为测试使用,业务请勿使用</li>\n</ol>\n</blockquote>\n<blockquote>\n<ol start=\"2\">\n<li>该接口仅支持图片上传,其他文件类型接口请自备</li>\n</ol>\n</blockquote>\n","order":"8"},"codes":{"jsx":"import { Upload, Button } from '@alifd/next';\n\nconst extraRender = (file) => {\n    console.log(file);\n    return (<Button style={{marginLeft: 4}}>extra</Button>);\n};\n\nReactDOM.render((\n    <Upload\n        listType=\"image\"\n        action=\"https://www.easy-mock.com/mock/5b713974309d0d7d107a74a3/alifd/upload\"\n        accept=\"image/png, image/jpg, image/jpeg, image/gif, image/bmp\"\n        beforeUpload={beforeUpload}\n        onChange={onChange}\n        extraRender={extraRender}\n        defaultValue={[{\n            name: 'IMG.png',\n            state: 'done',\n            size: 100,\n            url: 'https://img.alicdn.com/tps/TB19O79MVXXXXcZXVXXXXXXXXXX-1024-1024.jpg',\n        }]}\n    >\n        <Button type=\"primary\" style={{margin: '0 0 10px'}}>Upload File</Button>\n    </Upload>\n), mountNode);\n\nfunction beforeUpload(info) {\n    console.log('beforeUpload callback : ', info);\n}\n\nfunction onChange(info) {\n    console.log('onChange callback : ', info);\n}\n"},"body":"\n\n````jsx\nimport { Upload, Button } from '@alifd/next';\n\nconst extraRender = (file) => {\n    console.log(file);\n    return (<Button style={{marginLeft: 4}}>extra</Button>);\n};\n\nReactDOM.render((\n    <Upload\n        listType=\"image\"\n        action=\"https://www.easy-mock.com/mock/5b713974309d0d7d107a74a3/alifd/upload\"\n        accept=\"image/png, image/jpg, image/jpeg, image/gif, image/bmp\"\n        beforeUpload={beforeUpload}\n        onChange={onChange}\n        extraRender={extraRender}\n        defaultValue={[{\n            name: 'IMG.png',\n            state: 'done',\n            size: 100,\n            url: 'https://img.alicdn.com/tps/TB19O79MVXXXXcZXVXXXXXXXXXX-1024-1024.jpg',\n        }]}\n    >\n        <Button type=\"primary\" style={{margin: '0 0 10px'}}>Upload File</Button>\n    </Upload>\n), mountNode);\n\nfunction beforeUpload(info) {\n    console.log('beforeUpload callback : ', info);\n}\n\nfunction onChange(info) {\n    console.log('onChange callback : ', info);\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nvar extraRender = function extraRender(file) {\n    console.log(file);\n    return React.createElement(\n        _next.Button,\n        { style: { marginLeft: 4 } },\n        \"extra\"\n    );\n};\n\nReactDOM.render(React.createElement(\n    _next.Upload,\n    {\n        listType: \"image\",\n        action: \"https://www.easy-mock.com/mock/5b713974309d0d7d107a74a3/alifd/upload\",\n        accept: \"image/png, image/jpg, image/jpeg, image/gif, image/bmp\",\n        beforeUpload: beforeUpload,\n        onChange: onChange,\n        extraRender: extraRender,\n        defaultValue: [{\n            name: 'IMG.png',\n            state: 'done',\n            size: 100,\n            url: 'https://img.alicdn.com/tps/TB19O79MVXXXXcZXVXXXXXXXXXX-1024-1024.jpg'\n        }]\n    },\n    React.createElement(\n        _next.Button,\n        { type: \"primary\", style: { margin: '0 0 10px' } },\n        \"Upload File\"\n    )\n), mountNode);\n\nfunction beforeUpload(info) {\n    console.log('beforeUpload callback : ', info);\n}\n\nfunction onChange(info) {\n    console.log('onChange callback : ', info);\n}})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Upload<span class=\"token punctuation\">,</span> Button <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">extraRender</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span>file<span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n    console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span>file<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token keyword\">return</span> <span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>marginLeft<span class=\"token punctuation\">:</span> <span class=\"token number\">4</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">extra</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Upload</span>\n        <span class=\"token attr-name\">listType</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>image<span class=\"token punctuation\">\"</span></span>\n        <span class=\"token attr-name\">action</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>https://www.easy-mock.com/mock/5b713974309d0d7d107a74a3/alifd/upload<span class=\"token punctuation\">\"</span></span>\n        <span class=\"token attr-name\">accept</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>image/png, image/jpg, image/jpeg, image/gif, image/bmp<span class=\"token punctuation\">\"</span></span>\n        <span class=\"token attr-name\">beforeUpload</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>beforeUpload<span class=\"token punctuation\">}</span></span>\n        <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>onChange<span class=\"token punctuation\">}</span></span>\n        <span class=\"token attr-name\">extraRender</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>extraRender<span class=\"token punctuation\">}</span></span>\n        <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">[</span><span class=\"token punctuation\">{</span>\n            name<span class=\"token punctuation\">:</span> <span class=\"token string\">'IMG.png'</span><span class=\"token punctuation\">,</span>\n            state<span class=\"token punctuation\">:</span> <span class=\"token string\">'done'</span><span class=\"token punctuation\">,</span>\n            size<span class=\"token punctuation\">:</span> <span class=\"token number\">100</span><span class=\"token punctuation\">,</span>\n            url<span class=\"token punctuation\">:</span> <span class=\"token string\">'https://img.alicdn.com/tps/TB19O79MVXXXXcZXVXXXXXXXXXX-1024-1024.jpg'</span><span class=\"token punctuation\">,</span>\n        <span class=\"token punctuation\">}</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">}</span></span>\n    <span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>margin<span class=\"token punctuation\">:</span> <span class=\"token string\">'0 0 10px'</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Upload File</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Upload</span><span class=\"token punctuation\">></span></span>\n<span class=\"token punctuation\">)</span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">function</span> <span class=\"token function\">beforeUpload</span><span class=\"token punctuation\">(</span>info<span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n    console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span><span class=\"token string\">'beforeUpload callback : '</span><span class=\"token punctuation\">,</span> info<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span>\n\n<span class=\"token keyword\">function</span> <span class=\"token function\">onChange</span><span class=\"token punctuation\">(</span>info<span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n    console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span><span class=\"token string\">'onChange callback : '</span><span class=\"token punctuation\">,</span> info<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}
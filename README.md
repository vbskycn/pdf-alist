# pdf

自用pdf预览

**解决跨域问题**

![image-20240524091500095](https://img-cloud.zhoujie218.top/2024/05/24/664fea1f49659.png)

https://www.zhoujie218.top/archives/2623.html







官方网站

https://github.com/mozilla/pdf.js/releases







**alist调用**

https://pdf-alist.zhoujie218.top/web/viewer.html



```
{
	"doc,docx,xls,xlsx,ppt,pptx": {
		"Microsoft":"https://view.officeapps.live.com/op/view.aspx?src=$e_url",
		"Google":"https://docs.google.com/gview?url=$e_url&embedded=true"
	},
	"pdf": {
		"PDF.js":"https://pdf-alist.zhoujie218.top/web/viewer.html?file=$e_url"
	}
}
```








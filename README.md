# httplab
test for http
## ref

- [httpie github](https://github.com/jakubroztocil/httpie)
- [httpie 中英文对照](https://coyee.com/article/compare/10915-httpie-cli-http-client-user-friendly-curl-replacement-with-intuitive-ui)
- [httpie 入门](http://blog.csdn.net/pzw_0612/article/details/46521965)

## python
直接将python 目录和 python 下的scripts 目录加到环境变量下 
pyhton 中有 python.exe Scripts 下游 pip.exe
pip install 下载到 lib /site-packages 下
## tip

```c#
        // GET ajax/values/5
        //http :1234/api/ajax/get id==1
        //http :1234/api/ajax/get/1
          public string Get(int id)
        {

            return "valudde"+id.ToString();
        }

          //ref http://www.cnblogs.com/babycool/p/3922738.html
        //$.ajax({
        //    type: "Post",
        //    url: "http://localhost:1234/api/ajax/post",
        //    data: { '':'liz'},
        //    success: function(data) {
        //        window.console.dir(data);
        //    }
        //});
        //echo = liz | http -f  post http://localhost:1234/api/ajax/post
        //http -v -f  post http://localhost:1234/api/ajax/post =liz  Cookie:valued-visitor=yes;foo=bar
        public string Post([FromBody]string value)
        {
            return string.Format("name: {0}", value);
        }


 ```       

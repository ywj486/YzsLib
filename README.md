# YzsLib
       
        远程依赖方法在项目根目录下的build.gradle添加如下
        allprojects {
        		repositories {
        			...
        			<!--添加的话，就这一句-->
        			maven { url "https://jitpack.io" }
        		}
        	}


        在引用项目处添加
        dependencies {
        	        compile 'com.github.a243981326:YzsLib:0.0.2'
        	}
        
        
        目前最新版本为0.0.2，就是最新的release版本，之后引用修改版本号就可以 
        
        一个共享的资源库，本人会逐渐完善，让他越来越完美
        * 16.10.23 更新了NoticeView，公告条控件，支持绑定activity与fragment生命周期
        * 16.10.24 更新了base类
        * 16.11.3 更新控件nicespiner（美观又动画的自定义spinner），toggleButton（仿苹果滑动按钮）

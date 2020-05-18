# xcode11_upload_ipa
用于在xcode11及以上版本的ipa上传至iTunes Connect/AppStoreConnect


1. 使用AppleScript 和shell脚本写了一个简化的ipa上传流程
2. 双击即可运行，源文件可以用Mac电脑上的[自动操作]软件打开
3. 源码可以自由编辑，apiKey=''，apiIssuer='' 可以填入所需要的参数，这样就可以把由输入框输入的内容简化到了只需要选择ipa文件
4. 上传的过程中会打开~/目录，并且创建了log.txt文件，用来记录上传的流程信息，上传成功与否都会在log.txt看到相关信息。

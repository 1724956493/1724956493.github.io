# 项目特有的、待完善的、第三方的组件,以及对UI库中个别组件修改后的文件  

 - **描述：**  插件市场上第三方组件,以及项目中特有的组件，不涉及具体业务 ，

 - **使用方式：** 在页面中直接使用，不需要import和component注册, 

- **命名规则：** 项目中特有的或还未经过项目检验的组件，以“sel-具体组件名”的方式命名”，文件夹名与vue文件名必须相同 , 最外层view的class以当前组件名字命名
>- 引入的插件市场上第三方组件，需要在原有的名字前加“ex-”.方便查看业务代码时定位
>- 对UI库中个别组件修改，需要在原有的名字前加“modify-”

 ``` javascirpt
 <sel-dynamic-form></sel-dynamic-form>
 ```
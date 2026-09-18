# YYSLS-Package

适配于燕云十六声的3Dmigoto DX11的Package包

# 说明

由于版本更新后，新增了一套布料解算系统，所以生成的Mod不得不对其Shader进行修改，从而让Mod替换正常生效。

代价就是所有替换模型的部位布料解算都会失效。

注意此Package使用VSCheck架构，要在MMT中对每个生效的场景生成VSCheck才能正常使用，如有疑问可自行添加GlobalCheck，或者提交合适的Global Check的PR到此仓库。

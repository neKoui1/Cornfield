# Cornfield
 a simple blog web test with the implementation of gin & vue

Learn this from this [tutorial video](https://www.bilibili.com/video/BV1AA411v7e6/?spm_id_from=333.999.0.0&vd_source=1de02805632cb3d18d7f383a4105f328)

And you can stop by the original project, here is its [github website](https://github.com/wejectchen/Ginblog)

# Presentation

![163a4c517141c06d75186091611c6753](https://user-images.githubusercontent.com/77609544/225785104-2d611ede-a757-4fd2-aa3c-64866e47d172.jpg)

![bebfca7f2c5a3cc317195d7daec6a016](https://user-images.githubusercontent.com/77609544/225785489-2d467413-14f7-4c55-8422-791b003639de.jpg)


![12327e4771f052f9046ed635d0f82d3c](https://user-images.githubusercontent.com/77609544/225785453-f8cf0cf3-3c10-4126-8e2f-055fcb8e84e5.jpg)

![137d4d323c143d408d2f8edddb9f4714](https://user-images.githubusercontent.com/77609544/225785498-15a6eb2a-b30c-4609-843e-df6e8d50c44c.jpg)

![fc2ab65135227ae69607ca240128ca26](https://user-images.githubusercontent.com/77609544/225785507-27c88c95-054a-49b8-97a5-b35fa7d72d9f.jpg)

![78669717b5d893a984262c6355f2570d](https://user-images.githubusercontent.com/77609544/225785532-d0d66c5f-b73a-4c80-ab97-3e68550ab2d6.jpg)

![eefd32d8f4bf2da5aabaec48c2041850](https://user-images.githubusercontent.com/77609544/225785579-51fed04e-15d1-4deb-8723-f723110387c8.jpg)

# Technology Stack
* Backend
    * gin
    * gorm
    * logrus
    * jwt-go + bcrypt
    * go-cors
    * go-ini
* Frontend
    * vue
    * vue-cli
    * vue-router
    * vuetify
    * axios
    * tinymce
    * moment.js

But still know little about visualization & frontend, I could only copy the vue framework docs :<
    
# Summarize
1. The blog is written for my freshman roommate, but he absolutely does not use it because he does not hava an understanding of project deployment, neither do I. LOL
2. Learn logrus to record every SQL statement in the background.
3. Learn jwt-go & bcrypt for user encryption. Bcrypt encrption is preferred due to its dynamic transformation. It is time to abondon you, md5! (However, I can not read a single word of the paper about bcrypt on the official website T^TMATHS IS DIFFICULTTTTTTT)
4. At least know how to avoid cors problems in a go project.
5. The project can support only one user and there is no regulation and error handling for concurrent mutex. But the biggest advantage of go is channel & goroutine. How can I use it in later projects?
6. Let's rock another turn!

# myPortofolio (submission project dicoding learning path Become a Google Cloud Engineer)
### This is a submission project learning path Become a Google Cloud Engineer on  Modul dicoding platform

----
<h2>Getting Started</h2>
<h3 >

Step 1

</h3>
First, Create new Project in Google Cloud Console.


<h3 >

Step 2

</h3>

Copy the `Code` below using the clone command as follows on Cloud Shell :


```sh
git clone https://github.com/suryaLuqman/submission1-Proyek-Deploy-Aplikasi-Profile.git
```

<h3 >

Step 4

</h3>

```sh
> cd submission1-Proyek-Deploy-Aplikasi-Profile
```

<h3 >

Step 5

</h3>
Create bucket

```sh
> Navigation menu -> Cloud Storage -> Bucket. 
> Create
```

**Next, fill out the form as desired**<br>
***example***
| setting | value |
| ------ | ------ |
| Name | dicoding-storage-angkaunik |
| Location type dan Location | asia-southeast2 |
| Default storage class | Standard |
| Access control | Fine-grained. |

**Create**

<h3 >

Step 5

</h3>
Upload folder images, assets and another file to your bucket

```sh
> menu -> Upload Folder
```

Add participants 

```sh
> menu -> Permission -> +Grant Access 
```
| setting | value |
| ------ | ------ |
| new participant | allUsers |
| select a role | cloud storage -> storage object viewer |

**Save**

<h3 >

Step 6

</h3>
duplication your tab browser (tab2) -> Open Cloud Editor

```sh
> Cloud Shell  -> Open Editor -> Select your project 
```

open www/index.js

```sh
> edit link https://storage.googleapis************* to your file on cloud storage
```

```sh
> open tab 1 -> your bucket -> click folder -> click url public access 
```

<h3 >

Step 7

</h3>
Create App Engine

```sh
> Open tab 1 -> Navigation menu -> App engine 
> Create 
``` 

***exaple***
| setting | value |
| ------ | ------ |
| region | asia-southeast2 |
| Identity and API Access |App Engine Default Service Account |

**Next -> I’ll do this later**

<h3 >

Step 7

</h3>
deploy your web to App Engine

```sh
> Open tab 2 -> open cloud Shell editor -> open terminal 
> cd submission1-Proyek-Deploy-Aplikasi-Profile
> gcloud app deploy
> enter 'Y'
``` 

**to check your website active**
```sh
> gcloud app browse
> copy link below and paste your browser
``` 


## Thanks  😊👋😁

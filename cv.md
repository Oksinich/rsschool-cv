# Oksana Unashkhotleeva
## Contact information
* **tg** @Okzinich 
* **inst** okzini4 
## About me
I am an Android mobile developer with 2,5 years of experience in the industry. 
I have a strong background in Java and Kotlin programming languages, and I have developed Android applications
ranging from simple games to enterprise-level applications.
Overall, as an Android mobile developer, my goal is to create high-quality, user-friendly applications that meet customer needs. I strive to stay up-to-date with industry best practices and new technologies.

The desire to study does not leave me, and in addition to going to university, I decided to try myself in another direction  and learn frontend.
When it comes to working in a team, I am skilled at collaborating with other developers and project managers to deliver quality projects on time.

Learning frontend is important for me for several reasons:
* Frontend training can help you look at the product from different angles. 
* Improving the user experience. Frontend developers are working to improve the user experience, making websites and applications more convenient and functional. This will help me better understand the design for mobile devices as well. 

## Skills
* Kotlin 
* Java 
* Android Studio 
* Git, GitHub 
* Figma 
* DI
* XML
* SQLite
## Code example
```
bgInteractor.observerFor(ImgurSearchTask::class.java)
			.onLoading { task ->
				if (listWidget.size() == 0) {
					loadingWidget.showLoading()
				} else {
					refreshWidget.show()
				}
			}
			.onError { task, error ->
				if (listWidget.size() == 0) {
					loadingWidget.showFailed()
				} else {
					refreshWidget.hide()
					toaster.show("Не удалось обновить данные")
				}
			}
			.onSuccess { task, data ->
				refreshWidget.hide()
				loadingWidget.showLoaded()
				renderAlbums(data!!)
			}
			.subscribe()
```
## Work experience
* 2021-... Android developer "Drom".
## Education
* 2018-2021 Tomsk College of Information Technologies.
* 2022-2026 Tomsk State University of Control Systems and Radio Electronics.
* Udemy Android Multithreading Masterclass.
## Languages
* English - B1-B2. I have been taking English language improvement courses for a month now.
* Russian - Native.

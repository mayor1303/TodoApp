"# AndroidToDo" 
=======
## TODO.



---

## Features
Sign-IN                   |  Register                    | Adding Task             |  Adding Task SpeechToText
:----------------------------:|:--------------------------------------:|:----------------------:|:-----------------
<img src = "https://i.imgur.com/BOhKlzZ.gif" width="200" height="360"> |<img src = "https://imgur.com/rdOwtfs.gif" width="200" height="360">|<img src = "https://imgur.com/30IPruO.gif" width="200" height="360">|<img src = "https://imgur.com/y02gh9g.gif" width="200" height="360">
 #
Undo         |  Menu-DeleteAllTask                  | Menu-ImplicitIntent|      Notificaton
:----------------------------:|:--------------------------------------:|:----------------------:|:-----------------
 <img src = "https://imgur.com/0gZC18P.gif" width="200" height="360"> |   <img src = "https://imgur.com/NrTgyDt.gif" width="200" height="360">        | <img src = "https://imgur.com/DxR9kMG.gif" width="200" height="360">   | <img src = "https://imgur.com/Ae44D3S.gif" width="200" height="360">
 ---

### Design Architecture 



# MODEL
* `adapter`  consists of recyclerviews adapters.<br>
-`SwipeLeftDelete`<br>
-`TodoListCallbacks`<br>
* `Database` consists of dao(class for room database) ,UserAuthentication,db..<br>
-`DataAccessObject`<br>
-`AppDatabase`<br>
-`Dateconvert`<br>
-`RegisterUserAuthentication`<br>
-`TodoLists`<br>


# `VIEW`

* `Data`  consists of all the datas i.e notification, session, task, user<br>
*`Screens` consists all the screens i.e addeditTask, login, menu, splash, tasks <br>



# `ViewModel`

* `LoginRegisterViewModel`  <br>
* `LogoutViewModel` <br>
* `AddEditTaskViewModel` <br>
* `SplashViewModel` <br>
* `DeleteAllViewModel` <br>
* `MainActivityViewModel` <br>

---

## Documentation (Model–view–viewmodel architecture in a nutshell) 
Model–view–viewmodel (MVVM) is a software architectural pattern that facilitates the separation of the development of the graphical user interface (the view) be it via a markup language or GUI code from the development of the business logic or back-end logic (the model) so that the view is not dependent on any specific model platform. The view model of MVVM is a value converter,meaning the view model is responsible for exposing (converting) the data objects from the model in such a way that objects are easily managed and presented. In this respect, the view model is more model than view, and handles most if not all of the view's display logic.The view model may implement a mediator pattern, organizing access to the back-end logic around the set of use cases supported by the view.
#
![](https://codelabs.developers.google.com/codelabs/android-room-with-a-view-kotlin/img/a7da8f5ea91bac52.png)

---
>>>>>>> 377d4097772ace6cbcafd19f9fefaf7da9b78266

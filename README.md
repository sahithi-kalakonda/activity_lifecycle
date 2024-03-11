CMPE-277 – Assignment 1:

Activity Lifecycle

In this application, We have incremented the thread counter whenever the Main Activity restarts to demonstrate that when a new activity (Activity B, Activity C) is opened and we go back to the previous activity, onRestart() method is called. We increment the thread counter by 5.

On the other hand, when a dialog Activity is opened, and we go back to the previous activity, onRestart() method is not called, so the thread counter remains unchanged.

Home screen:

<img width="201" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic1.png?raw=true">

</br>

Activity B opened:
</br>
<img width="200" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic2.png?raw=true">
</br>
Count incremented by 5:
</br>
<img width="222" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic3.png?raw=true">
</br>
</br>
Activity C opened:
</br>
<img width="222" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic4.png?raw=true">
</br>
Count incremented to 15:
</br>
</br>

<img width="232" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic5.png?raw=true">

</br>
Dialog opened:
</br>
</br>
<img width="231" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic%206%20.png?raw=true">
</br>
Count remains unchanged:
</br>
</br>
<img width="232" alt="image" src="https://github.com/hhh99-hub/Android_Lifecycle/blob/main/Images/pic5.png?raw=true">







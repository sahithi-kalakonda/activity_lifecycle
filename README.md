CMPE-277  Assignment

Activity Lifecycle

In our app, we've increased the thread counter each time the Main Activity restarts to show that reopening previous activities like Activity B or Activity C triggers the onRestart() method, adding 5 to the counter. However, when we open a dialog Activity and return to the previous one, onRestart() isn't invoked, leaving the thread counter unchanged.

Home screen:

<img width="201" alt="image" src="Images/pic1.jpeg">

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







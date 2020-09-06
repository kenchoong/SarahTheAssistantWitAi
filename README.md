# SarahTheAssistantWitAi
Sarah is your virtual private assistant. Sarah will help you organize your daily life to record your expenses,todo list,shopping list without using your hand.Of course you want to use hand, is ok too. 

# Support well on Android device from Android version 6.0 to Android 10(minSdkVersion 21, targetSdkVersion 29) 
- Tested working well on Oppo F5, Android 7.1.1, API Level 26
- Tested working well on Redmi 3s, Android 6.0, API Level 23
- Tested working well on Realme 2 pro, Android 10, API Level 29

# Testing scenario

When first start of the app, will have an Onboard experience for new user.

Please give permission for write storage and record voice.

When Sarah ask you "Can I continue? "
- Say YES or OK : To continue to next presentation
- Say NO : To skip the onboard experience 

Click the Mic at the bottom to let Sarah listen to you, you can click again to let it stop      
Sarah need to listen your voice for 5 seconds, then send to Wit.ai, then response to you.       
You can see the countdown timer at the visualizer.      

You can see the HD live conversation without any editing here: (https://www.youtube.com/watch?v=Spa0Zt1Rrt0) 

To test with main function of the app:
- Say Chicken eleven (Expenses name + number/money) - Record as expenses
- Say Pick up my son 7 am tmr (Task name + Time) - Record as To do list
- Say Shopping List Iphone ("Shopping list" + Item) - Record as Shopping list 

You can just give half of the record: 
- Say :Chicken (Only a verb) - Will ask you how much you spend for it
- Say :Pick up my son (Only task) - Will ask you the time
- Say: Jonathon(Only a name) - will ask you the task u want to do with Jonathon and time
- If a random sentences(Cant figure out what to do nex) - will ask you what is it for
- Then you can answer: RECORD to do list/ expenses / shopping list (Record is the keyword) 
- Then it will go through and do the action. 

Test for the special command
- Say: Start record to do list - This will continously taking to do list, it assume what you say next is a to do task
- Say: Show my total - Will give you total expenses of the day
- Say: Show my to do list - Will give you all to do task you recorded 
- Say: Show my shopping list- Will give you all item in the list 

When Sarah ask: Anything else?
If say: Nothing else, That's all, this will cancel all previous operation

Check what you recorded and listen your input by clicking button at the top bar

Click keyboard button to interact using Text.

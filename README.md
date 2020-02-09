# ClauBoard (MindIT On-Board Process)

Hello!

My name is ClauBoard and i am here to help you regarding the on-board process. 
I am very efficient since i am built in UiPath but i am not a complete robot yet. I am very sure that you can help me with some updates when you have the right time.
Note: At this moment i can only do the MindIT On-Boarding process and i plan in the near future that i can be more of a model in order to be adapted in each company.

# Prerequisites

I will try to keep it simple in order to point out only the important things:
1. I need to have the e-mail's employee activated before i start the process because i will send him some e-mails (And his Windows must be already active and configured);
2. The Profile ID picture must be placed inside the robot's directory (Ex: cbbb74d9-9597-4632-ac29-ed6801a01c87.jfif) and the full name must be inserted inside the Excel parameters (Data\Angajat.xlsx - Poza Buletin).

# Future Developments

Okay, i will list all my future improvements that will be implemented and i will sort them by priority:
1. Passwords must be stored inside the Orchestrator or on the Windows machine in order to avoid having passwords inside the angajat.xlsx;
- For this one we will need to connect to Orchestrator and to create a queue in order to get the credentials from the queue;
2. Add actions when an exception is triggered inside the States -> Entry -> Try/Catch -> Catch;
- For the moment, we will add a send outlook mail with the exception to the HR's mail;
3. Organize, Re-name and add anotations in order to better understand the whole project since we don't have any technical documentation;

Having in mind that we've said the top priority things, we will now just list the other stuff:
1. Make a circular flow with Statuses/Indicators that are updated depending on the states in order to optimize the flow (If we are making this, we don't need anymore studio installed OR to connect to the remote machine since we will only just copy paste the Excel File into a location and the whole process will be automatically triggered at each 10/15 minutes)
2. I don't have anymore to add at this moment but if you want to improve me please send ideas/suggestions to claudiu.vaida@mindit.io.

And the last thing, i want to thank to the following people that have created me : 
- Claudiu Vaida
- Lucian Cismaru
- Vlad Munteanu
- Claudia Politeanu

Hope that it was not boring. Thank you again!

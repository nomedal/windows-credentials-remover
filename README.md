# windows-credentials-remover
A simple script to remove windows credentials, under crendentials manager. Will not remove web credentials.
# Usage
    Run file from file explorer or terminal, or automate as scheduled task.



# How to make the script run at set time interval
- Open `Task scheduler`.
- Open `Create Basic task...` under `Actions>Create Baisc Task...`.
- On the `Create a Basic Task` tab, add a `Name` and `Description`.
- On the `Trigger` tab, we can choose whatver we like, we'll edit this later anyway.
- Under `Action` choose `Start a program`, all other options are deprecated.
	- Under `Program/script`, browse to the `.cmd` or `.bat` file, or whaterver else you want to run, add optional arguments and preferences if so desired.
- After making the task, find it under `Task Scheduler Library`.
- Right click, go to `Properties>Triggers`.
- Choose the trigger we want to edit, press `Edit` on the bottom panel.
- Here you can choose time interval, and further adjust settings.
# Requirement Evolution
Making a comparison between the state of the requirements at the beginning of the project, and the final state of them now in the final increment, we can see some main differences:

## User Requirements
* At the beginning, without a specific platform, the user requirements were more oriented to the main functions the project's system should be able to have as functionalities instead of now, as we have the selected platform, they are more specific.

## Functional Requirements
* Through the first two increments of the project, some functional requirements were modified to be clearer and specify with more detail the actions the system should permit, examples of this would be:
  * The user roles actions are now divided into the specific functions they have as part of their role, an example being how only managers should be able to delete entries, instead of the first iteration where both the manager and moderators were able to do it.
  * The evaluation criteria are now used for the reviewing of each entry, but, as it's a task for the moderator, the users with this type of role should be the only ones able to review a post, meaning that now managers have task more oriented to the administrative part of the system.
* With the selection and implementation of a specific platform the objective of containing sections is already achieved with the platform itself, so would no longer enter as a system requirement.

## Non-functional Requirements
* The main evolution would be seen from the amount of the requirements planted at the beginning and the amount of them at the end, going from seven to only 4, and even though there are less in the final version, now we only use the necessary ones:
  * Showing feedback to an user after submitting data lacks the idea of also showing feedback when using any function of the system which is a non-told requirement every system should have, hence why is no longer included as a written requirement.
  * With the option of having "anonymous authors" for post entries, makes the condition of entering a username restrictive, as now the user can both introduce a name or leave blank that element without a problem in the system functionality.
  * As a bot, the welcoming message is no longer necessary, as is present in a server all the time waiting for the user's accepted command.
  * Although the platform is structure with a Graphic User Interface (GUI), the bot works based on a Command-Line Interface (CLI), so the system now includes both type of interfaces contrary to the requirement set at the beginning.
  * The moderators should only be able to review entries, so they cannot change the content of any entry and should not be able to access all the system functionalities.
  * As the platform makes use of accounts, now is necessary to have a Discord account to be able to use the system of the bot itself.


♦[Main Page](https://github.com/Edwin-Lines/Project-Cosmos/tree/Third-Deadline) 

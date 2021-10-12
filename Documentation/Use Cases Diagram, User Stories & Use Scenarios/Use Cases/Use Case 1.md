# Use Case 1

|Use Case |Actors |Type|Pre-condition |Post-condition|Author|Date| Purpose|
|---------|-------|----|--------------|--------------|------|----|--------|
|Creates text entry|User, Platform, Database|Essential|The user has access to the platform|The text entry is registered in the database and returned to a main screen.|Fernan|28/09/2021|Register a user’s text entry|

|Summary|
|-------|
|A user accesses the platform used and enters the desired text entry according to the conditions that the text entry must meet and uploads/sends the text entry. Upon submission, the text entry is registered into the database and the platform returns to the home page before entering the text entry.|

|Normal course|
|-------------|
|1. The user enters the platform|
|2. Type in the text field the entry to be saved|
|3. Click to send (or a similar feature)|
|4. The system registered text input to the database.
|5. The system prints successfeedback|
|6. The platform is returned to its initial state (empty in the shipping field)|

|Alternative courses|
|-------------------|
|4a. The system does not register text entry to the database|
|5a. The system prints fault feedback and goes to 6|

##### Other data
|Importance |Urgency|State|Comments|
|-----|-----|----------|---------------------------------------------------|
|High | High| pending |Look for possible platforms to perform the deployment|


# Custom Testcase Generator using Langflow API

A customizable testcase generator that allows you to modify input and output parameters while keeping the implementation hidden.

### Step 1: Extract the API from Langflow
1. Go to **Langflow → Share → API Access**
2. Copy the URL from the localhost
3. Copy the Request Body
4. Copy the Langflow API Key from your Profile (top right corner)

### Step 2: Create a Postman Collection
1. Open Postman and create a new Collection
2. Create a POST request
3. Paste the copied URL and Request Body from Step 1

### Step 3: Add the API Key in Postman
1. Go to the Headers tab in Postman
2. Add a new key: `x-api-key`
3. Paste the Langflow API Key as the value

### Step 4: Customize the Input and Output Parameters
Configure the following parameters as needed:
- **Prompt Template:** Template
- **Groq:** Groq API Key, Temperature, Model

### Step 5: Validate the Response
1. Click Send
2. Validate the response in Postman

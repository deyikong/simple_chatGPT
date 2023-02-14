## Setup

1. Clone this repository

2. Install the requirements

   ```bash
   $ ./bin/yarn install
   ```

3. Make a copy of the example environment variables file

   On Linux systems: 
   ```bash
   $ cp .env.example .env
   ```
   On Windows:
   ```powershell
   $ copy .env.example .env
   ```
4.Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

5.Run the app locally

   ```bash
   $ yarn dev
   ```

LOG IN TO SUPABASE
##(STEP 1)
Create a supabase Account
Open Supabase.
Login using your gmail account.
create a new project.
Remember that the free supabase have a limited number of free projects.

##(STEP 2)
Created the Database Table.
Open your supabase project.
create or paste your SQL schema.
Run the SQL file.

Create Table Department (
    department id INT PRIMARY KEY,
    department name VARCHAR(100) NOT NULL,
    Location VARCHAR(100) NOT NULL,
);

##(STEP 3)
Get supabase environment variables.
open your supabase project.
click the connect button at the top.
open the environment variables section.
open the supabase URL and API Key.

##(STEP 4)
Create the NEXT.JS PROJECT
Open command prompt (CMD) and run.
cd desktop.
npx create-next-app@latest maria-sup.
cd maria-sup.
npm install @supabase/supabase-js.
npm run dev.
The Next.jd project will be created with the name maria-sup.

##(STEP 5)
Open the project in VS STUDIO CODE(
Open the maria-sup folder in visual studio code.
The basic structure will look like:
maria-sup
app
package.json
public
);

##(STEP 6)
Create .env.local
craete a file named.
.env.local
in the root folder of the page

NEXT_PUBLIC_SUPABASE_URL=Your supabase URL1
NEXT-PUBLIC-SUPABASE-ANON KEY=your supabase key

##(STEP 7)
Create the lib folder
create a folder name
inside the lib folder,create
maria-sup
app
lib
supabase.js
.env.local
package j.son

##(STEP 8)
Create the supabase client
open lib supabase .js and write:
import { createclient } from "supabase/supabase-js";

export const supabase = createclient(
    process.env.
)










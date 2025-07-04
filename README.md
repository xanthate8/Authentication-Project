Wasn't able to deploy to Render, Netlify, etc. 


These are env file data (just for viewing purposes):
SESSION_SECRET="TOPSECRETWORD"
PG_USER="postgres"
PG_HOST="db.ivxfviqxvsjjxprfwjpc.supabase.co"
PG_DATABASE="postgres"
PG_PASSWORD="dagHvd56_09djcbhD3Gdgh"
PG_PORT="5432"


Used supabase for storing and comparing the data.


Used bcrypt for hasing passwords and salted the passwords several times(10).

Used passport, express session for authentication and maintaining user info for sometime so that they don't need to login again and can directly access the "secrets" page.




Here is my reflection on this weeks assignment. For this weeks assignment I noted down on paper my reflections as a devlog. This is the first time using this method and I think I will be continuing with this for future projects. I've noted mistakes down before but not step by step actions that were done to complete the assisgnment

## Dev log

1. Deployed on Vercel  to see errors & bugs.
2. Created tables in Supabase that were provided
3. Uncommented the UNIQUE_ID
4. Created an .env file
5. Did npm i and installed packages needed
6. Ran npm run dev to see errors in console
7. Added Supabase transaction code
8. Added OAuth Git Keys to .env
9. Added variables to Vercel
10. Deployed successful after changing .env
11. Issues with the log-in - wasnt able to understand why. I changed the github url to the vercel url and still recieved error. Added screenshot of error page to submission (ignore screenshot😂)
12. Made Dynamic Metadata


## What I Found Difficult
OAuth Authentication & Debugging:
The login functionality was the most challenging part. Even after updating the GitHub OAuth callback URL from localhost to the Vercel deployment URL, authentication errors persisted. The error messages weren't clear about what was wrong, making it hard to pinpoint whether the issue was with the callback URL format or something else entirely. After going into breakout room with Bertie, I was able to identify that the links I used from Vercel weren't the correct ones. After correcting this I was able to log in and everytihng was functioning perfectly fine.

## Helpful Links

https://nextjs.org/docs/app/api-reference/functions/generate-metadata
https://www.youtube.com/watch?v=H-1ozULYdyc

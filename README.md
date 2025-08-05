# JobBridge-Job-Referral-Portal
This is an open-source project using React and SpringBoot.

Below are the User Stories. Contact me at kajolmurmu.13292@gmail.com if you want to contribute.

🔥 User Stories, Pages & APIs
Each user story below shows what the user can do, the main page they’ll use, and the core backend API endpoint.

Registration & Sign-In

I want to create an account or log in—my email type (work/personal) sets my role.

Page: /signup, /login

API: POST /api/auth/signup, POST /api/auth/login

Profile Setup & Email Verification

I want to set up my professional profile and verify my email.

Page: /profile

API: PUT /api/users/{id}, POST /api/auth/verify-email

Company Domain Whitelisting

I (admin) want to manage which company domains allow work email roles.

Page: /admin/company-domains

API: GET/POST/DELETE /api/admin/company-domains

Browse Job Feed

I want to explore all jobs and referrals, filtering as needed.

Page: /jobs

API: GET /api/jobs?filters

View Job/Referral Details

I want to see full details for any job or referral post.

Page: /jobs/{id}

API: GET /api/jobs/{id}

Apply to Job or Request Referral

I want to submit a job application or a referral request.

Page: /jobs/{id}/apply

API: POST /api/jobs/{id}/apply

Post New Job (Work Email Only)

As a work-email user, I want to post job openings at my company.

Page: /jobs/new

API: POST /api/jobs

Post Referral Opportunity (Work Email Only)

As a work-email user, I want to offer to refer others to open roles.

Page: /referrals/new

API: POST /api/referrals

Manage My Posts (Jobs & Referrals)

I want to see, edit, or delete posts I’ve created.

Page: /my-posts

API: GET /api/users/{id}/posts, PUT /api/jobs/{id}, DELETE /api/jobs/{id}

View & Manage Applicants

As a work-email user, I want to review applicants and manage their status.

Page: /my-posts/{postId}/applications

API: GET /api/jobs/{id}/applications, PUT /api/applications/{appId}

Save/Bookmark Jobs

I want to save jobs or referrals and revisit them later.

Page: /saved

API: POST/DELETE /api/users/{id}/saved, GET /api/users/{id}/saved

Search Jobs & Referrals

I want to search postings by title, company, or keyword.

Page: /jobs?search

API: GET /api/jobs?search=

Notifications

I want to get notified about applications, responses, or new opportunities.

Page: /notifications

API: GET /api/notifications, POST /api/notifications/read

Messaging on Referrals

I want to message professionals with work emails about potential referrals.

Page: /messages

API: POST /api/messages, GET /api/messages/{threadId}

Admin Moderation Dashboard

As an admin, I want to manage users, domains, and moderate posts.

Page: /admin/dashboard

API: GET /api/admin/users, PUT /api/admin/posts/{id}/status, DELETE /api/admin/users/{id}


_ If you reading... I just starting huh!!

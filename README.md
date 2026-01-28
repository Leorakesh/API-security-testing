# API-security-testing
Day 35 of 100 days of challenge 

Day 35 – API Security Testing: Broken Authentication & Authorization

On Day 35, I focused on API security testing, specifically identifying broken authentication and authorization flaws that expose backend services to attackers. Since modern applications rely heavily on APIs, weaknesses here can lead to full account takeover, data leakage, and privilege escalation.

What I Learned

How APIs handle authentication tokens (JWT, API keys, sessions).

Common causes of Broken Object Level Authorization (BOLA).

Differences between authentication vs authorization in API flows.

How attackers bypass access controls using ID manipulation.

Why missing role checks lead to privilege escalation.

Techniques Practiced

Testing APIs with Postman / Burp Suite.

Modifying user IDs and tokens in requests.

Checking for unauthorized access to protected endpoints.

Validating token expiration and scope handling.

Verifying HTTP methods (GET, POST, PUT, DELETE) abuse.

Vulnerabilities Observed

Accessing other users’ data by changing object IDs.

Missing role validation on admin endpoints.

Reusing expired or weak tokens.

Insecure direct object references (IDOR).

Over-privileged API responses.

Key Takeaways

API security is not just about logging in — it’s about ensuring every request is properly authorized. Broken authentication and authorization allow attackers to move laterally, escalate privileges, and compromise entire systems. Proper validation, least privilege, and consistent access checks are critical for secure APIs.

If you want, I can also add:
A shorter version
A portfolio-style version
Tools section
OWASP API Top 10 mapping
Markdown badges

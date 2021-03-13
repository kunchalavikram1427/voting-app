Example Voting App
=========
This is a simple application based on micro-services architecture, consisting of 5 simple services.

Voting-App: Frontend of the application written in Python, used by users to cast their votes.
Redis: In-memory database, used as intermediate storage.
Worker: .Net service, used to fetch votes from Redis and store in Postgres database.
DB: PostgreSQL database, used as database.
Result-App: Frontend of the application written in Node.js, displays the voting results.


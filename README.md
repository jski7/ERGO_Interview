# Ergo - Interview task solution

1. Create Git repository https://github.com/jski7/ERGO_Interview.git
2. Create folder for analytics and db
3. Download template db
4. Install Docker
5. Create Dockerfile for jupyter-notebook
6. Create docker-compose file with 
   1. jupyter notebook, 
   2. Postgres
   3. pgadmin4 - database visualisation and manual management
7. Build containers
8. Log in into pgadmin
9. Connect to postgres server
   1. hostname: postgress
   2. login: postgres
   3. password: changeme
10. Manually create movies database in pgadmin
11. Manually create tables
12. Manually insert data from csv
13. Log into Jupyter via browser - token: hi
14. Resolve tasks in Jupyter notebook (5 out of 6 resolved)
15. Translate Database initiation manual actions to SQL queries
16. Merge Database initialisation file and task solution file
17. Clean up database and containers 
18. Test solution from scratch
19. Remove pgadmin
20. Test script without pgadmin

### Build from scratch
1. Pull repo
2. Change to repository directory 
3. Run command docker-compose up --build
4. Log into Jupyter via browser - token: hi
5. Run /analytics/Solution.ipynb
6. DB with tables and links is initiated, data imported from csv
7. Answers are printed as Solution.ipynb output

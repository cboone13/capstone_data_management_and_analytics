## capstone_data_management_and_analytics
Project proposal and implementation plan - Streamlining Data Migration from PostgreSQL to SQL Server

### Project Topic 

HS Advantage Inc. a mid-size home school curriculum provider, is currently working on
building a data warehouse for in-house reporting services. They currently use a PostgreSQL database
but are switching to a SQL Server environment. They have built a solution that is experiencing slow
migration performance when moving data from PostgreSQL v9.2 to their new SQL Server database.

### Problem Statement 

The process of retrieving data from a PostgreSQL 9.2 server
containing 55 tables to populate tables in a SQL Server database using a SQL Server Integration
Services (SSIS) solution takes approximately 8 hrs of processing time. The target goal of the runtime
of this process is 1 hour. Due to the long runtime of 8 hours the current solution is not viable. SQL
Solutions Group. has been brought in to improve the process to ensure the business requirements are
met.

### Project Scope

#### Project Goal(s) and Supporting Objectives –

     i.   Conduct exploration with HS Advantage Inc. to bring SQL Solutions Group up to date
             on the current process and how it works.
     ii.  Determine what changes to the current process are needed to ensure a consistent
             runtime of 1 hour or less is achieved.
     iii. Develop and implement changes to increase the performance of moving data from a
             PostgreSQL 9.2 databse to a SQL Server database using SQL Server Integration
             Services (SSIS) from 8 hours to a target of 1 hour.
     iv.  Conduct handover from SQL Solutions Group to HS Advantage Inc. and ensure they
             understand how the new process works and how to maintain it.
             
#### Project Outcomes and Deliverables –

     i.   A positive outcome will be when the process of moving data takes 1 hour or less to
             complete.
     ii.  HS Advantage Inc. will be giving a SQL Server Integration Services (SSIS) solution
             that will meet the time constraints of this objective.
     iii. HS Advantage Inc. will understand how the new process works and how to properly
             maintain it.
             
#### Projected Project End Date –

     i. The project should take 5 weeks to complete. This will give the
        project an approximate completion date of September 25th XXXX. This will ensure SQL
        Solutions Group has the time needed to perform proper evaluation, development,
        implementation, and training to HS Advantage Inc. IT staff.

### IMPLEMENTATION and EVALUATION
There will be 4 phases to this project. Each of which will contain a milestone to measure progress throughout.

#### Phase 1: Discovery – Research the root cause of the long runtime.
              Measureable – Root cause is identified, understood, and documented.
             
#### Phase 2: Design – Devise a solution to the root cause of poor performance.
              Measureable – Flow chart detailing the steps and changes to the current process.
              
#### Phase 3: Development – Building of the SSIS packages is conducted.
              Measureable – A Complete SSIS Solution is built and ready for deployment.
              
#### Phase 4: Testing and Implementation– SSIS Solution will be deployed to test environment.
                                          Each individual package will be timed and monitored for performance as well as the whole
                                          process to ensure the 1 hour goal is met.
              Measureable – Complete solution deployed to production environment and
                            running at a regular interval with a consistent runtime of under 1 hour.
                            
#### Phase 5: Handoff – SQL Solutions Group will train HS Advantage Inc. IT department on how the new 
                        process works and how to properly maintain the solution.
              Measureable - HS Advantage Inc. IT department can describe how the process
                            works and demonstrate the skills necessary to perform regular maintenance and
                            troubleshooting.


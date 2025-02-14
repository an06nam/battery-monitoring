# A Battery Monitoring System NOT A BMS

### NOTE

This repo serve as an all in one services for me to get and proces the data form a real BMS that I want to build.
Though the idea are generally "do/able", it isn't something that I could run with my cheap dirt pocket.

Nonetheless, lest start from something that can be done without making me starve first.


## FEATURES IN DEVELOPMENT

### Backend

- [ ] Create a Connection to database (postgresql) and the required table
- [ ] Create a CRUD operation
- [ ] Read stream data form mqtt and write to the database
- [ ] Create custom binary messages to seamlessly communicate with microcontroller
- [ ] Optimize the database read & write process
- [ ] Create an extensive API to communicate with frontend
- [ ] Create UNIT TEST

### Frontend

- [ ] Create a functional account base login if needed
- [ ] Create a monitoring UI that are show graph and table
- [ ] an other things that should be pretty, it is a frontend afterall

## MAYBE a NICE FEATURE TO HAVE

### DATA PROCESS

- [ ] a machine learning code to process the data
- [ ] get the data from backend, process it, dump it back to backend.
- [ ] Just use python for this

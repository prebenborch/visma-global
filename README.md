# Visma.net 

### Prerequisites local development
- Visma global server only available from vm instance-3
- Local development can be done via a ssh tunnel via vm instance-3
- In order to setup the ssh tunnel developers need ssh access on instance-3

### Setting up the ssh tunnel for local developmen
Command in terminal window ```ssh -L localhost:8082:51.107.214.108:8082 visma-global.storeshop.no -N```

### installation process
To start this app you should follow this instruction:
1. max `node js` version should be `13.13.0`
2. `npm i`
3. start postgres 13
4. create all databases from the `ormconfig.json`
5. `npm start` 


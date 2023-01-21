### docker ps -> check all the containers status


1. cd in to artifacts/channel/create-certificate-with-ca and run docker composer with docker-compose up -d -> created 4 containers for those services.

2. Then create certificates authority(crypto materials) for organizations with executing ./create-certificate-with-ca.sh -> This will create the crypto-config folder.

3. Create artifacts and create the genesis block with ./create-artifacts.sh.

4. Run all the services or all the instances with running ./docker-compose.yaml inside artifacts folder with docker-compose up -d.

5. Create the channel and join to channel with ./createChannel.sh in the root directory.

6. Deploy the chaincode with ./deployChaincode.sh in the root directory.
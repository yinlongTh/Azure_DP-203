## Decide how many storage accounts you need

#### Storage
- SQL : Can't be in Storage Accounts
- Cosmos DB : Can't be in Storage Accounts
- Events Hubs
- Azure Storage : Tables, Queues, Files, Blobs
Resource Group -> Storage Accounts (AD, Role based, Own 2 keys) -> Azure Storages

#### Database Properties
- Durable
- Secure
- Scalable
- Managable

<strong>Azure Storage</strong>
- Blob : Back up, Storing fole, Streaming media
  - Block : Media files 100 mb/block
  - Page 
  - Append
- Files : Sharable by SMB protocal which makes VMs access the same file
- Queues : Message management

<strong>Shared Access Signatures</strong>
- Use with un-trusted clients
- Service Level : Read
- Account Level : Read, Write

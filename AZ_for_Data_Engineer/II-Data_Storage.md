## Storage
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

#### Blob
- Semi or Non-structured
- up to 8 TB for VMs, Analysis, Back up
- Video, audio
- No Actual file system
<pre>
<strong>Block Blobs</strong>
- Up to 100 MB
- Up to 50k Data points (blocks)
- Max over 4.7 TB 

<strong>Append Blobs</strong>
- Like Blobk Blobs 
- Append only, No Update or Delete
- Max 195 GB
- writting logs 

<strong>Page Blobs</strong>
- Hold VMs
- Up to 8 TB
- Support random read and write
</pre>

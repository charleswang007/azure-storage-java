# azure-storage-java

### Command

1. from Command Prompt
```
cd blob-quickstart
set AZURE_STORAGE_CONNECTION_STRING="xxxxxx"
mvn compile
mvn package
mvn exec:java -D exec.mainClass=com.blobs.quickstart.App -D exec.cleanupDaemonThreads=false
```

### Reference

- https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-java?tabs=powershell%2Cmanaged-identity%2Croles-azure-portal%2Csign-in-azure-cli

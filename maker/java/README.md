# db maker java implementation

### 1, How to build ?
```
ant all
```
Managing multiple Java versions
Identify known RIAs. In order to whitelist RIAs and delegate certain RIAs to specific Java versions, the first step is to identify where those applications are.
Install Java versions through patch-in-place or static installation mode. ...
Deploy the latest version of Java. ...
Delegate certain RIAs to use specific Java versions. ...

### 2, How to make ?
```
java -jar dbMaker-{version}.jar -src path of ip.merge.txt -region path of global_region.csv -dst ip2region.db target path
```

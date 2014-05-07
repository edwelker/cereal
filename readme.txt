1. mvn archetype:create -DgroupId=gov.nih.nlm.ncbi -DartifactId=java_avro_example
2. Add the dependency and plugins to your pom.xml
   * note: remember to put the plugin inside <build><plugins></></>

3. If you want to build by hand (without mvn) get the avro tools package (http://apache.mirrors.hoobly.com/avro/avro-1.7.6/java/avro-tools-1.7.6.jar), if you want to use maven, just mvn compile

4. create your avro schema file, in src/main/avro/whatever.avsc, making sure that your namespace is "gov.nih.nlm.ncbi.avro"



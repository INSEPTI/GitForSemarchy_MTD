<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_BDXjEF4CEe6CVaUmkEockA" name="Datamart" md:ref="resource.md#UUID_MD_RDBMS_HYPERSONIC_SQL?fileId=UUID_MD_RDBMS_HYPERSONIC_SQL$type=md$name=Hypersonic%20SQL?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_BDhUEV4CEe6CVaUmkEockA" value="HSQL"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_Dy_LAF4CEe6CVaUmkEockA" value="sa"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_Dy_LAV4CEe6CVaUmkEockA" value="org.hsqldb.jdbcDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_Dy_LAl4CEe6CVaUmkEockA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_Dy_LA14CEe6CVaUmkEockA" value="jdbc:hsqldb:hsql://localhost:62211"/>
  <node defType="com.stambia.rdbms.schema" id="_BO1zQF4CEe6CVaUmkEockA" name="PUBLIC">
    <attribute defType="com.stambia.rdbms.schema.name" id="_BO_kQF4CEe6CVaUmkEockA" value="PUBLIC"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_BO_kQV4CEe6CVaUmkEockA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_BO_kQl4CEe6CVaUmkEockA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_BO_kQ14CEe6CVaUmkEockA" value="I_[targetName]"/>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_JBB9MF4CEe6CVaUmkEockA" name="DATAMART">
    <attribute defType="com.stambia.rdbms.schema.name" id="_JBU4IF4CEe6CVaUmkEockA" value="DATAMART"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_JBU4IV4CEe6CVaUmkEockA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_JBYigF4CEe6CVaUmkEockA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_JBYigV4CEe6CVaUmkEockA" value="I_[targetName]"/>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_QWGmQF8TEe6PHahGNfrU1Q" name="HOTEL_DATAMART">
    <attribute defType="com.stambia.rdbms.schema.name" id="_QZJ6QF8TEe6PHahGNfrU1Q" value="HOTEL_DATAMART"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_QZKhUF8TEe6PHahGNfrU1Q" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_QZLIYF8TEe6PHahGNfrU1Q" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_QZLvcF8TEe6PHahGNfrU1Q" value="I_[targetName]"/>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_SmdfUF8TEe6PHahGNfrU1Q" name="INFORMATION_SCHEMA">
    <attribute defType="com.stambia.rdbms.schema.name" id="_SnG_kF8TEe6PHahGNfrU1Q" value="INFORMATION_SCHEMA"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_SnG_kV8TEe6PHahGNfrU1Q" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_SnG_kl8TEe6PHahGNfrU1Q" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_SnG_k18TEe6PHahGNfrU1Q" value="I_[targetName]"/>
  </node>
</md:node>
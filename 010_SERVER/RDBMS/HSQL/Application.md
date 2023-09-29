<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_YOaGUF4CEe6CVaUmkEockA" name="Application" md:ref="resource.md#UUID_MD_RDBMS_HYPERSONIC_SQL?fileId=UUID_MD_RDBMS_HYPERSONIC_SQL$type=md$name=Hypersonic%20SQL?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_YOjQbl4CEe6CVaUmkEockA" value="HSQL"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_a5ZF4F4CEe6CVaUmkEockA" value="sa"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_a5ZF4V4CEe6CVaUmkEockA" value="org.hsqldb.jdbcDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_a5ZF4l4CEe6CVaUmkEockA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_a5ZF414CEe6CVaUmkEockA" value="jdbc:hsqldb:hsql://localhost:62210"/>
  <node defType="com.stambia.rdbms.schema" id="_YbzCEF4CEe6CVaUmkEockA" name="HOTEL_MANAGEMENT">
    <attribute defType="com.stambia.rdbms.schema.name" id="_Yb8MAF4CEe6CVaUmkEockA" value="HOTEL_MANAGEMENT"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_Yb8MAV4CEe6CVaUmkEockA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_Yb8MAl4CEe6CVaUmkEockA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_Yb8MA14CEe6CVaUmkEockA" value="I_[targetName]"/>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_KHcEkF8TEe6PHahGNfrU1Q" name="PUBLIC">
    <attribute defType="com.stambia.rdbms.schema.name" id="_KIi30F8TEe6PHahGNfrU1Q" value="PUBLIC"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_KIi30V8TEe6PHahGNfrU1Q" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_KIi30l8TEe6PHahGNfrU1Q" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_KIi3018TEe6PHahGNfrU1Q" value="I_[targetName]"/>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_N6yaYF8TEe6PHahGNfrU1Q" name="MOTEL">
    <attribute defType="com.stambia.rdbms.schema.name" id="_N8cnQF8TEe6PHahGNfrU1Q" value="MOTEL"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_N8cnQV8TEe6PHahGNfrU1Q" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_N8cnQl8TEe6PHahGNfrU1Q" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_N8hfwF8TEe6PHahGNfrU1Q" value="I_[targetName]"/>
  </node>
</md:node>
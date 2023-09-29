<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_AsvbiV8VEe6PHahGNfrU1Q" name="Hotel Management" md:ref="resource.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_Asvbil8VEe6PHahGNfrU1Q" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_Asvbi18VEe6PHahGNfrU1Q" value="C:\Stambia\Semarchy\semarchy-xdi-designer\runtime\samples\xml\hotelManagement.xsd"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="_AsvbjF8VEe6PHahGNfrU1Q" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="_AsvbjV8VEe6PHahGNfrU1Q" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="_Asvbjl8VEe6PHahGNfrU1Q" value="http://stambia.org/samples/management"/>
  <node defType="com.stambia.xml.namespace" id="_Asvbj18VEe6PHahGNfrU1Q" name="http://stambia.org/samples/common">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_AsvbkF8VEe6PHahGNfrU1Q" value="com"/>
  </node>
  <node defType="com.stambia.xml.root" id="_AsvbkV8VEe6PHahGNfrU1Q" name="marketingCampaign" position="0">
    <attribute defType="com.stambia.xml.root.xmlPath" id="_Asvbkl8VEe6PHahGNfrU1Q" value="C:\Stambia\Logiciels\Designer\stambiaDesigner_S18.3.3_20170816_120540\stambia\stambiaRuntime\samples\xml\marketingCampaign.xml"/>
    <node defType="com.stambia.xml.sequence" id="_Asvbk18VEe6PHahGNfrU1Q" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvblF8VEe6PHahGNfrU1Q" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvblV8VEe6PHahGNfrU1Q" value="1"/>
      <node defType="com.stambia.xml.element" id="_Asvbll8VEe6PHahGNfrU1Q" name="phoningCampaign" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvbl18VEe6PHahGNfrU1Q" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvbmF8VEe6PHahGNfrU1Q" value="1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_AsvbmV8VEe6PHahGNfrU1Q" value="mgt:PhoningCampaign"/>
        <node defType="com.stambia.xml.attribute" id="_Asvbml8VEe6PHahGNfrU1Q" name="campaignId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvbm18VEe6PHahGNfrU1Q" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvbnF8VEe6PHahGNfrU1Q" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvbnV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvbnl8VEe6PHahGNfrU1Q" name="name" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvbn18VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvboF8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvboV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvbol8VEe6PHahGNfrU1Q" name="startDate" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvbo18VEe6PHahGNfrU1Q" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvbpF8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvbpV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvbpl8VEe6PHahGNfrU1Q" name="endDate" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvbp18VEe6PHahGNfrU1Q" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvbqF8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvbqV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Asvbql8VEe6PHahGNfrU1Q" position="7">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Asvbq18VEe6PHahGNfrU1Q" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvbrF8VEe6PHahGNfrU1Q" value="1"/>
          <node defType="com.stambia.xml.element" id="_AsvbrV8VEe6PHahGNfrU1Q" name="customer" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvbrl8VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvbr18VEe6PHahGNfrU1Q" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_AsvbsF8VEe6PHahGNfrU1Q" name="customerId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbsV8VEe6PHahGNfrU1Q" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbsl8VEe6PHahGNfrU1Q" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvbs18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvbtF8VEe6PHahGNfrU1Q" name="titleCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbtV8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbtl8VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvbt18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvbuF8VEe6PHahGNfrU1Q" name="title" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbuV8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbul8VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvbu18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvbvF8VEe6PHahGNfrU1Q" name="firstName" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbvV8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbvl8VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvbv18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvbwF8VEe6PHahGNfrU1Q" name="lastName" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbwV8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbwl8VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvbw18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvbxF8VEe6PHahGNfrU1Q" name="company" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbxV8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbxl8VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvbx18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvbyF8VEe6PHahGNfrU1Q" name="birthDate" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvbyV8VEe6PHahGNfrU1Q" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvbyl8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvby18VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_AsvbzF8VEe6PHahGNfrU1Q" position="10">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvbzV8VEe6PHahGNfrU1Q" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Asvbzl8VEe6PHahGNfrU1Q" value="1"/>
              <node defType="com.stambia.xml.element" id="_Asvbz18VEe6PHahGNfrU1Q" name="phone" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvb0F8VEe6PHahGNfrU1Q" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvb0V8VEe6PHahGNfrU1Q" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="_Asvb0l8VEe6PHahGNfrU1Q" value="com:Phone"/>
                <node defType="com.stambia.xml.attribute" id="_Asvb018VEe6PHahGNfrU1Q" name="phoneId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Asvb1F8VEe6PHahGNfrU1Q" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb1V8VEe6PHahGNfrU1Q" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Asvb1l8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Asvb118VEe6PHahGNfrU1Q" name="phoneTypeCode" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Asvb2F8VEe6PHahGNfrU1Q" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb2V8VEe6PHahGNfrU1Q" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Asvb2l8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Asvb218VEe6PHahGNfrU1Q" name="phoneNumber" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Asvb3F8VEe6PHahGNfrU1Q" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb3V8VEe6PHahGNfrU1Q" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Asvb3l8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Asvb318VEe6PHahGNfrU1Q" name="phoneType" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Asvb4F8VEe6PHahGNfrU1Q" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb4V8VEe6PHahGNfrU1Q" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Asvb4l8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_Asvb418VEe6PHahGNfrU1Q" name="phoningAllowed" position="4">
                  <attribute defType="com.stambia.xml.attribute.type" id="_Asvb5F8VEe6PHahGNfrU1Q" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb5V8VEe6PHahGNfrU1Q" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_Asvb5l8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
      <node defType="com.stambia.xml.element" id="_Asvb518VEe6PHahGNfrU1Q" name="mailingCampaign" position="1">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvb6F8VEe6PHahGNfrU1Q" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvb6V8VEe6PHahGNfrU1Q" value="1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Asvb6l8VEe6PHahGNfrU1Q" value="mgt:MailingCampaign"/>
        <node defType="com.stambia.xml.attribute" id="_Asvb618VEe6PHahGNfrU1Q" name="campaignId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvb7F8VEe6PHahGNfrU1Q" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb7V8VEe6PHahGNfrU1Q" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Asvb7l8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvb718VEe6PHahGNfrU1Q" name="name" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvb8F8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb8V8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Asvb8l8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvb818VEe6PHahGNfrU1Q" name="startDate" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvb9F8VEe6PHahGNfrU1Q" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb9V8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Asvb9l8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvb918VEe6PHahGNfrU1Q" name="endDate" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvb-F8VEe6PHahGNfrU1Q" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvb-V8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Asvb-l8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Asvb-18VEe6PHahGNfrU1Q" position="7">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Asvb_F8VEe6PHahGNfrU1Q" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Asvb_V8VEe6PHahGNfrU1Q" value="1"/>
          <node defType="com.stambia.xml.element" id="_Asvb_l8VEe6PHahGNfrU1Q" name="customer" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvb_18VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvcAF8VEe6PHahGNfrU1Q" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_AsvcAV8VEe6PHahGNfrU1Q" name="customerId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcAl8VEe6PHahGNfrU1Q" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcA18VEe6PHahGNfrU1Q" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcBF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcBV8VEe6PHahGNfrU1Q" name="titleCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcBl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcB18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcCF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcCV8VEe6PHahGNfrU1Q" name="title" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcCl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcC18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcDF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcDV8VEe6PHahGNfrU1Q" name="firstName" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcDl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcD18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcEF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcEV8VEe6PHahGNfrU1Q" name="lastName" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcEl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcE18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcFF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcFV8VEe6PHahGNfrU1Q" name="company" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcFl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcF18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcGF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcGV8VEe6PHahGNfrU1Q" name="birthDate" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvcGl8VEe6PHahGNfrU1Q" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcG18VEe6PHahGNfrU1Q" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcHF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_AsvcHV8VEe6PHahGNfrU1Q" position="10">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvcHl8VEe6PHahGNfrU1Q" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvcH18VEe6PHahGNfrU1Q" value="1"/>
              <node defType="com.stambia.xml.element" id="_AsvcIF8VEe6PHahGNfrU1Q" name="email" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="_AsvcIV8VEe6PHahGNfrU1Q" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvcIl8VEe6PHahGNfrU1Q" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="_AsvcI18VEe6PHahGNfrU1Q" value="com:Email"/>
                <node defType="com.stambia.xml.attribute" id="_AsvcJF8VEe6PHahGNfrU1Q" name="emailId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvcJV8VEe6PHahGNfrU1Q" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcJl8VEe6PHahGNfrU1Q" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvcJ18VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_AsvcKF8VEe6PHahGNfrU1Q" name="emailAddress" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvcKV8VEe6PHahGNfrU1Q" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcKl8VEe6PHahGNfrU1Q" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvcK18VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_AsvcLF8VEe6PHahGNfrU1Q" name="emailType" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvcLV8VEe6PHahGNfrU1Q" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcLl8VEe6PHahGNfrU1Q" value="xs:string"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvcL18VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_AsvcMF8VEe6PHahGNfrU1Q" name="mailingAllowed" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvcMV8VEe6PHahGNfrU1Q" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcMl8VEe6PHahGNfrU1Q" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvcM18VEe6PHahGNfrU1Q" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
  <node defType="com.stambia.xml.namespace" id="_AsvcNF8VEe6PHahGNfrU1Q" name="http://stambia.org/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_AsvcNV8VEe6PHahGNfrU1Q" value="mgt"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_AsvcNl8VEe6PHahGNfrU1Q" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_AsvcN18VEe6PHahGNfrU1Q" value="xs"/>
  </node>
  <node defType="com.stambia.xml.root" id="_AsvcOF8VEe6PHahGNfrU1Q" name="customerSummary" position="0">
    <attribute defType="com.stambia.xml.root.xmlPath" id="_AsvcOV8VEe6PHahGNfrU1Q" value="C:\Temp\customerSummary.xml"/>
    <node defType="com.stambia.xml.sequence" id="_AsvcOl8VEe6PHahGNfrU1Q" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvcO18VEe6PHahGNfrU1Q" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvcPF8VEe6PHahGNfrU1Q" value="1"/>
      <node defType="com.stambia.xml.element" id="_AsvcPV8VEe6PHahGNfrU1Q" name="customer" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_AsvcPl8VEe6PHahGNfrU1Q" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvcP18VEe6PHahGNfrU1Q" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_AsvcQF8VEe6PHahGNfrU1Q" value="mgt:Customer"/>
        <node defType="com.stambia.xml.attribute" id="_AsvcQV8VEe6PHahGNfrU1Q" name="customerId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcQl8VEe6PHahGNfrU1Q" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcQ18VEe6PHahGNfrU1Q" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcRF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvcRV8VEe6PHahGNfrU1Q" name="titleCode" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcRl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcR18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcSF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvcSV8VEe6PHahGNfrU1Q" name="title" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcSl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcS18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcTF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvcTV8VEe6PHahGNfrU1Q" name="firstName" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcTl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcT18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcUF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvcUV8VEe6PHahGNfrU1Q" name="lastName" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcUl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcU18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcVF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvcVV8VEe6PHahGNfrU1Q" name="company" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcVl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcV18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcWF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvcWV8VEe6PHahGNfrU1Q" name="birthDate" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcWl8VEe6PHahGNfrU1Q" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcW18VEe6PHahGNfrU1Q" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcXF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
      </node>
    </node>
  </node>
  <node defType="com.stambia.xml.root" id="_AsvcXV8VEe6PHahGNfrU1Q" name="hotelManagement" position="0">
    <attribute defType="com.stambia.xml.root.xmlPath" id="_AsvcXl8VEe6PHahGNfrU1Q" value="C:\Temp\hotelManagement.xml"/>
    <node defType="com.stambia.xml.sequence" id="_AsvcX18VEe6PHahGNfrU1Q" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvcYF8VEe6PHahGNfrU1Q" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvcYV8VEe6PHahGNfrU1Q" value="1"/>
      <node defType="com.stambia.xml.element" id="_AsvcYl8VEe6PHahGNfrU1Q" name="customer" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_AsvcY18VEe6PHahGNfrU1Q" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvcZF8VEe6PHahGNfrU1Q" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_AsvcZV8VEe6PHahGNfrU1Q" value="mgt:CustomerDetail"/>
        <node defType="com.stambia.xml.attribute" id="_AsvcZl8VEe6PHahGNfrU1Q" name="customerId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvcZ18VEe6PHahGNfrU1Q" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcaF8VEe6PHahGNfrU1Q" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcaV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvcal8VEe6PHahGNfrU1Q" name="titleCode" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvca18VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcbF8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcbV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvcbl8VEe6PHahGNfrU1Q" name="title" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvcb18VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvccF8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvccV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvccl8VEe6PHahGNfrU1Q" name="firstName" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvcc18VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcdF8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcdV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvcdl8VEe6PHahGNfrU1Q" name="lastName" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvcd18VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvceF8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvceV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvcel8VEe6PHahGNfrU1Q" name="company" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvce18VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcfF8VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcfV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvcfl8VEe6PHahGNfrU1Q" name="birthDate" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvcf18VEe6PHahGNfrU1Q" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvcgF8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvcgV8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Asvcgl8VEe6PHahGNfrU1Q" position="10">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Asvcg18VEe6PHahGNfrU1Q" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvchF8VEe6PHahGNfrU1Q" value="1"/>
          <node defType="com.stambia.xml.element" id="_AsvchV8VEe6PHahGNfrU1Q" name="address" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvchl8VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvch18VEe6PHahGNfrU1Q" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_AsvciF8VEe6PHahGNfrU1Q" value="com:Address"/>
            <node defType="com.stambia.xml.attribute" id="_AsvciV8VEe6PHahGNfrU1Q" name="addressId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcil8VEe6PHahGNfrU1Q" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvci18VEe6PHahGNfrU1Q" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcjF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcjV8VEe6PHahGNfrU1Q" name="line1" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcjl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcj18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvckF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvckV8VEe6PHahGNfrU1Q" name="line2" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvckl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvck18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvclF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvclV8VEe6PHahGNfrU1Q" name="line3" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcll8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcl18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcmF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcmV8VEe6PHahGNfrU1Q" name="line4" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcml8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcm18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcnF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcnV8VEe6PHahGNfrU1Q" name="zipCode" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcnl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcn18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcoF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcoV8VEe6PHahGNfrU1Q" name="city" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcol8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvco18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcpF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcpV8VEe6PHahGNfrU1Q" name="stateCode" position="7">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcpl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcp18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcqF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_AsvcqV8VEe6PHahGNfrU1Q" name="phone" position="1">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvcql8VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvcq18VEe6PHahGNfrU1Q" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_AsvcrF8VEe6PHahGNfrU1Q" value="com:Phone"/>
            <node defType="com.stambia.xml.attribute" id="_AsvcrV8VEe6PHahGNfrU1Q" name="phoneId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcrl8VEe6PHahGNfrU1Q" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcr18VEe6PHahGNfrU1Q" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcsF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcsV8VEe6PHahGNfrU1Q" name="phoneTypeCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcsl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcs18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvctF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvctV8VEe6PHahGNfrU1Q" name="phoneNumber" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvctl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvct18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcuF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcuV8VEe6PHahGNfrU1Q" name="phoneType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcul8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcu18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcvF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcvV8VEe6PHahGNfrU1Q" name="phoningAllowed" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcvl8VEe6PHahGNfrU1Q" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcv18VEe6PHahGNfrU1Q" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcwF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_AsvcwV8VEe6PHahGNfrU1Q" name="email" position="2">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvcwl8VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvcw18VEe6PHahGNfrU1Q" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_AsvcxF8VEe6PHahGNfrU1Q" value="com:Email"/>
            <node defType="com.stambia.xml.attribute" id="_AsvcxV8VEe6PHahGNfrU1Q" name="emailId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcxl8VEe6PHahGNfrU1Q" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcx18VEe6PHahGNfrU1Q" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvcyF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvcyV8VEe6PHahGNfrU1Q" name="emailAddress" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvcyl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcy18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvczF8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvczV8VEe6PHahGNfrU1Q" name="emailType" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvczl8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvcz18VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc0F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Asvc0V8VEe6PHahGNfrU1Q" name="mailingAllowed" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc0l8VEe6PHahGNfrU1Q" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc018VEe6PHahGNfrU1Q" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc1F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_Asvc1V8VEe6PHahGNfrU1Q" name="bill" position="3">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvc1l8VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvc118VEe6PHahGNfrU1Q" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_Asvc2F8VEe6PHahGNfrU1Q" value="com:Bill"/>
            <node defType="com.stambia.xml.attribute" id="_Asvc2V8VEe6PHahGNfrU1Q" name="billId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc2l8VEe6PHahGNfrU1Q" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc218VEe6PHahGNfrU1Q" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc3F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Asvc3V8VEe6PHahGNfrU1Q" name="billDate" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc3l8VEe6PHahGNfrU1Q" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc318VEe6PHahGNfrU1Q" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc4F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Asvc4V8VEe6PHahGNfrU1Q" name="paymentTypeCode" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc4l8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc418VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc5F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Asvc5V8VEe6PHahGNfrU1Q" name="paymentType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc5l8VEe6PHahGNfrU1Q" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc518VEe6PHahGNfrU1Q" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc6F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Asvc6V8VEe6PHahGNfrU1Q" name="paymentDate" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc6l8VEe6PHahGNfrU1Q" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc618VEe6PHahGNfrU1Q" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc7F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Asvc7V8VEe6PHahGNfrU1Q" name="totalAmount" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="_Asvc7l8VEe6PHahGNfrU1Q" value="decimal"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc718VEe6PHahGNfrU1Q" value="xs:decimal"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Asvc8F8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
          </node>
        </node>
      </node>
      <node defType="com.stambia.xml.element" id="_Asvc8V8VEe6PHahGNfrU1Q" name="bedroom" position="1">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Asvc8l8VEe6PHahGNfrU1Q" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Asvc818VEe6PHahGNfrU1Q" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Asvc9F8VEe6PHahGNfrU1Q" value="mgt:Bedroom"/>
        <node defType="com.stambia.xml.attribute" id="_Asvc9V8VEe6PHahGNfrU1Q" name="bedroomId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvc9l8VEe6PHahGNfrU1Q" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc918VEe6PHahGNfrU1Q" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Asvc-F8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvc-V8VEe6PHahGNfrU1Q" name="roomNumber" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvc-l8VEe6PHahGNfrU1Q" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc-18VEe6PHahGNfrU1Q" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Asvc_F8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Asvc_V8VEe6PHahGNfrU1Q" name="floor" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Asvc_l8VEe6PHahGNfrU1Q" value="short"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Asvc_18VEe6PHahGNfrU1Q" value="xs:short"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdAF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvdAV8VEe6PHahGNfrU1Q" name="bath" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvdAl8VEe6PHahGNfrU1Q" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdA18VEe6PHahGNfrU1Q" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdBF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvdBV8VEe6PHahGNfrU1Q" name="shower" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvdBl8VEe6PHahGNfrU1Q" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdB18VEe6PHahGNfrU1Q" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdCF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvdCV8VEe6PHahGNfrU1Q" name="bar" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvdCl8VEe6PHahGNfrU1Q" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdC18VEe6PHahGNfrU1Q" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdDF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvdDV8VEe6PHahGNfrU1Q" name="bedCount" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvdDl8VEe6PHahGNfrU1Q" value="short"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdD18VEe6PHahGNfrU1Q" value="xs:short"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdEF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvdEV8VEe6PHahGNfrU1Q" name="phoneNumber" position="7">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvdEl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdE18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdFF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_AsvdFV8VEe6PHahGNfrU1Q" name="bedroomType" position="8">
          <attribute defType="com.stambia.xml.attribute.type" id="_AsvdFl8VEe6PHahGNfrU1Q" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdF18VEe6PHahGNfrU1Q" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_AsvdGF8VEe6PHahGNfrU1Q" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_AsvdGV8VEe6PHahGNfrU1Q" position="12">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvdGl8VEe6PHahGNfrU1Q" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvdG18VEe6PHahGNfrU1Q" value="1"/>
          <node defType="com.stambia.xml.element" id="_AsvdHF8VEe6PHahGNfrU1Q" name="priceRange" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_AsvdHV8VEe6PHahGNfrU1Q" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvdHl8VEe6PHahGNfrU1Q" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_AsvdH18VEe6PHahGNfrU1Q" name="startDate" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvdIF8VEe6PHahGNfrU1Q" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdIV8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvdIl8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvdI18VEe6PHahGNfrU1Q" name="endDate" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvdJF8VEe6PHahGNfrU1Q" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdJV8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvdJl8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_AsvdJ18VEe6PHahGNfrU1Q" name="price" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_AsvdKF8VEe6PHahGNfrU1Q" value="decimal"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdKV8VEe6PHahGNfrU1Q" value="xs:decimal"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_AsvdKl8VEe6PHahGNfrU1Q" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_AsvdK18VEe6PHahGNfrU1Q" position="6">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="_AsvdLF8VEe6PHahGNfrU1Q" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_AsvdLV8VEe6PHahGNfrU1Q" value="1"/>
              <node defType="com.stambia.xml.element" id="_AsvdLl8VEe6PHahGNfrU1Q" name="occupation" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="_AsvdL18VEe6PHahGNfrU1Q" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_AsvdMF8VEe6PHahGNfrU1Q" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="_AsvdMV8VEe6PHahGNfrU1Q" value="com:Occupation"/>
                <node defType="com.stambia.xml.attribute" id="_AsvdMl8VEe6PHahGNfrU1Q" name="customerId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvdM18VEe6PHahGNfrU1Q" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdNF8VEe6PHahGNfrU1Q" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvdNV8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_AsvdNl8VEe6PHahGNfrU1Q" name="occupationDate" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvdN18VEe6PHahGNfrU1Q" value="dateTime"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdOF8VEe6PHahGNfrU1Q" value="xs:dateTime"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvdOV8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_AsvdOl8VEe6PHahGNfrU1Q" name="personCount" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvdO18VEe6PHahGNfrU1Q" value="short"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdPF8VEe6PHahGNfrU1Q" value="xs:short"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvdPV8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_AsvdPl8VEe6PHahGNfrU1Q" name="booked" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="_AsvdP18VEe6PHahGNfrU1Q" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="_AsvdQF8VEe6PHahGNfrU1Q" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="_AsvdQV8VEe6PHahGNfrU1Q" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>
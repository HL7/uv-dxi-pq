The HTML rendering below shows a synthetic Quality data example for Common Technical Document (CTD) Module 3: Quality, section 3.2.P.3 Manufacture, subsection 3.2.P.3.3 Description of Manufacturing Process and Process Controls and subsection 3.2.P.3.4 Controls of Critical Steps and Intermediates.
<html>
<body>
<div class="divBody">
<p>
						This is the same data as in the example files here in <a href="Bundle-bundle-product-manufacturing-pq-ex1.xml.html">xml</a> and in <a href="Bundle-bundle-product-manufacturing-pq-ex1.json.html">json</a>, presented for easier viewing.
						Hovering on words below will show the corresponding sections of the underlying data.
					</p>
</div>
<div class="greyable">
<div class="divBody">
<div style="position:relative" class="summaryUnit">
<div class="debugOffBorder">
<div class="bundleBorder">
<div class="debugOff">
<div class="bundle"><a class="plainLink"><span class="bold" title="Bundle (id: bundle-product-manufacturing-pq-ex1)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-product-manufacturing-pq 

<Bundle>
    <!-- Product Manufacturing -->
    <id value=&quot;bundle-product-manufacturing-pq-ex1&quot;/>
    <meta>
        <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-product-manufacturing-pq&quot;/>
    </meta>
    <type value=&quot;collection&quot;/>
    <entry>
        <fullUrl value=&quot;urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265a&quot;/>
        <resource>
            <PlanDefinition>
                <id value=&quot;manufacturingProcess-unlinked&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq&quot;/>
                </meta>
                <extension url=&quot;http://nprogram.co.uk/fhir/extension/viewer/tabulateEquipment&quot;>
                    <valueBoolean value=&quot;true&quot;/>
                </extension>
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-plan-document-reference-pq&quot;>
                    <valueReference>
                        <!-- Process flow diagram -->
                        <!-- or could be a Binary -->
                        <reference value=&quot;DocumentReference/documentreference-drug-pq-process-flow-diagram&quot;/>
                    </valueReference>
                </extension>
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-history-of-process-pq&quot;>
                    <valueMarkdown value=&quot;This can be text about the history&quot;/>
                </extension>
                <url value=&quot;http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a&quot;/>
                <title value=&quot;Process 1.0&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/plan-definition-type&quot;/>
                        <code value=&quot;workflow-definition&quot;/>
                        <display value=&quot;Workflow Definition&quot;/>
                    </coding>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-plan-type&quot;/>
                        <code value=&quot;manufacturing-process&quot;/>
                        <display value=&quot;Manufacturing Process&quot;/>
                    </coding>
                </type>
                <status value=&quot;active&quot;/>
                <subjectReference>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </subjectReference>
                <description value=&quot;Narrative description of manufacturing process (5)&quot;/>
                <goal id=&quot;goal-control-pH&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - pH&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>
                            </coding>
                            <text value=&quot;pH must be in range 6.9 to 7.1&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </low>
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <goal id=&quot;goal-control-water-content&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Water Content&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>
                            </coding>
                            <text value=&quot;Under 2%&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Particle Size&quot;/>
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>
                            </coding>
                            <text value=&quot;Under 200 microns&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/mixing-vessel&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>
                        </role>
                    </option>
                </actor>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/receiving-tank&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>
                        </role>
                    </option>
                </actor>
                <!-- outer action is the whole thing, if needed -->
                <!-- step 1 mixing -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;1&quot;/>
                    <description value=&quot;Mixing of ingredients&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>
                        </coding>
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-pH&quot;/>
                    <!--goalId value=&quot;goal-control-temp&quot;/-->
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/mixer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/startingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/processingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;processing material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <!--action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlPH&quot;/>
                        </action>
                        <action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlTemperature&quot;/>
                        </action-->
                </action>
                <!-- step 2 drying -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <!-- todo want a range here -->
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;2&quot;/>
                    <description value=&quot;Drying using a heater&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-water-content&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/dryer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                </action>
                <!-- step 3 particle size -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;3&quot;/>
                    <description value=&quot;Particle Size Reduction by using a rotating impeller&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-particle-size&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/devicedefinition-drug-pq-ex1&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                </action>
            </PlanDefinition>
        </resource>
    </entry>
    <!-- Section 5.2 - Unit Operation/Equipment Information -->
    <entry>
        <fullUrl value=&quot;urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bad9494c&quot;/>
        <resource>
            <DeviceDefinition>
                <id value=&quot;devicedefinition-drug-pq-ex1&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DeviceDefinition-drug-pq&quot;/>
                </meta>
                <deviceName>
                    <name value=&quot;Rotating Impeller with 1.5mm screen&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum Speed&quot;/>
                            <display value=&quot;Maximum Speed&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;5000&quot;/>
                        <unit value=&quot;RPM&quot;/>
                    </valueQuantity>
                </property>
            </DeviceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bbd9494c&quot;/>
        <resource>
            <DeviceDefinition>
                <id value=&quot;dryer&quot;/>
                <deviceName>
                    <name value=&quot;Heated dryer&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Power&quot;/>
                            <display value=&quot;Power&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;3&quot;/>
                        <unit value=&quot;kW&quot;/>
                    </valueQuantity>
                </property>
            </DeviceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bad9494d&quot;/>
        <resource>
            <DeviceDefinition>
                <id value=&quot;mixer&quot;/>
                <deviceName>
                    <name value=&quot;Blender&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum capacity&quot;/>
                            <display value=&quot;Maximum capacity&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>
                </property>
            </DeviceDefinition>
        </resource>
    </entry>
    <!-- Section 5.1 - Manufacturing Process Overview - Process Flow Diagram -->
    <entry>
        <fullUrl value=&quot;urn:uuid:74d4c070-6596-8252-8ad9-afa515a41feb&quot;/>
        <resource>
            <DocumentReference>
                <id value=&quot;documentreference-drug-pq-process-flow-diagram&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DocumentReference-drug-pq&quot;/>
                </meta>
                <identifier>
                    <system value=&quot;http://example.org/fhir/identifier/document&quot;/>
                    <value value=&quot;FLOW-001&quot;/>
                </identifier>
                <status value=&quot;current&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/diagram-type&quot;/>
                        <code value=&quot;ProcessFlowDiagram&quot;/>
                        <display value=&quot;Process Flow Diagram&quot;/>
                    </coding>
                </type>
                <content>
                    <attachment>
                        <contentType value=&quot;image/x-png&quot;/>
                        <data value=&quot;iVBORw0KGgoAAAANSUhEUgAAAgQAAAApCAYAAABKrzFXAAAAAXNSR0IArs4c6QAAEjl0RVh0bXhmaWxlACUzQ214ZmlsZSUyMGhvc3QlM0QlMjJFbGVjdHJvbiUyMiUyMG1vZGlmaWVkJTNEJTIyMjAyMy0wNy0wNlQxMyUzQTA4JTNBMDguNDgzWiUyMiUyMGFnZW50JTNEJTIyTW96aWxsYSUyRjUuMCUyMChXaW5kb3dzJTIwTlQlMjAxMC4wJTNCJTIwV2luNjQlM0IlMjB4NjQpJTIwQXBwbGVXZWJLaXQlMkY1MzcuMzYlMjAoS0hUTUwlMkMlMjBsaWtlJTIwR2Vja28pJTIwZHJhdy5pbyUyRjIxLjYuMSUyMENocm9tZSUyRjExMi4wLjU2MTUuMjA0JTIwRWxlY3Ryb24lMkYyNC42LjElMjBTYWZhcmklMkY1MzcuMzYlMjIlMjBldGFnJTNEJTIyNkMxTlFraVpHaXdVNTVadFBEMUQlMjIlMjB2ZXJzaW9uJTNEJTIyMjEuNi4xJTIyJTIwdHlwZSUzRCUyMmRldmljZSUyMiUzRSUwQSUyMCUyMCUzQ2RpYWdyYW0lMjBpZCUzRCUyMkM1UkJzNDNvRGEtS2R6WmVOdHV5JTIyJTIwbmFtZSUzRCUyMlBhZ2UtMSUyMiUzRSUwQSUyMCUyMCUyMCUyMCUzQ214R3JhcGhNb2RlbCUyMGR4JTNEJTIyMTAzNiUyMiUyMGR5JTNEJTIyMTc4MyUyMiUyMGdyaWQlM0QlMjIxJTIyJTIwZ3JpZFNpemUlM0QlMjIxMCUyMiUyMGd1aWRlcyUzRCUyMjElMjIlMjB0b29sdGlwcyUzRCUyMjElMjIlMjBjb25uZWN0JTNEJTIyMSUyMiUyMGFycm93cyUzRCUyMjElMjIlMjBmb2xkJTNEJTIyMSUyMiUyMHBhZ2UlM0QlMjIxJTIyJTIwcGFnZVNjYWxlJTNEJTIyMSUyMiUyMHBhZ2VXaWR0aCUzRCUyMjgyNyUyMiUyMHBhZ2VIZWlnaHQlM0QlMjIxMTY5JTIyJTIwYmFja2dyb3VuZCUzRCUyMm5vbmUlMjIlMjBtYXRoJTNEJTIyMCUyMiUyMHNoYWRvdyUzRCUyMjAlMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlM0Nyb290JTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0wJTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0xJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMCUyMiUyMCUyRiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214Q2VsbCUyMGlkJTNEJTIyS2g2VVdDcUxFb3V5cUZPSzdudE0tOSUyMiUyMHZhbHVlJTNEJTIyJTIyJTIwc3R5bGUlM0QlMjJlbmRBcnJvdyUzRGNsYXNzaWMlM0JodG1sJTNEMSUzQnJvdW5kZWQlM0QwJTNCZXhpdFglM0QxJTNCZXhpdFklM0QwLjUlM0JleGl0RHglM0QwJTNCZXhpdER5JTNEMCUzQmVudHJ5WCUzRDAlM0JlbnRyeVklM0QwLjUlM0JlbnRyeUR4JTNEMCUzQmVudHJ5RHklM0QwJTNCJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUyMHNvdXJjZSUzRCUyMktoNlVXQ3FMRW91eXFGT0s3bnRNLTI1JTIyJTIwdGFyZ2V0JTNEJTIyRjYyX0J4bjByeDdnZzNWUllyNWgtMCUyMiUyMGVkZ2UlM0QlMjIxJTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhHZW9tZXRyeSUyMHdpZHRoJTNEJTIyNTAlMjIlMjBoZWlnaHQlM0QlMjI1MCUyMiUyMHJlbGF0aXZlJTNEJTIyMSUyMiUyMGFzJTNEJTIyZ2VvbWV0cnklMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteFBvaW50JTIweCUzRCUyMjQ4MS40MzAwMDAwMDAwMDAwNiUyMiUyMHklM0QlMjItNjAlMjIlMjBhcyUzRCUyMnNvdXJjZVBvaW50JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhQb2ludCUyMHglM0QlMjIzMDYlMjIlMjB5JTNEJTIyLTE2MCUyMiUyMGFzJTNEJTIydGFyZ2V0UG9pbnQlMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0MlMkZteEdlb21ldHJ5JTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJLaDZVV0NxTEVvdXlxRk9LN250TS0yNSUyMiUyMHZhbHVlJTNEJTIyU3RlcCUyMDElMjZsdCUzQmJyJTI2Z3QlM0IlMjZsdCUzQmklMjZndCUzQk1peGluZyUyNmx0JTNCJTJGaSUyNmd0JTNCJTIyJTIwc3R5bGUlM0QlMjJyb3VuZGVkJTNEMSUzQndoaXRlU3BhY2UlM0R3cmFwJTNCaHRtbCUzRDElM0Jmb250U2l6ZSUzRDEyJTNCZ2xhc3MlM0QwJTNCc3Ryb2tlV2lkdGglM0QxJTNCc2hhZG93JTNEMCUzQmZpbGxDb2xvciUzRCUyM2Y4Y2VjYyUzQnN0cm9rZUNvbG9yJTNEJTIzYjg1NDUwJTNCJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUyMHZlcnRleCUzRCUyMjElMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteEdlb21ldHJ5JTIweCUzRCUyMjEyMCUyMiUyMHklM0QlMjItMjMwJTIyJTIwd2lkdGglM0QlMjIxMjAlMjIlMjBoZWlnaHQlM0QlMjI0MCUyMiUyMGFzJTNEJTIyZ2VvbWV0cnklMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0MlMkZteENlbGwlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteENlbGwlMjBpZCUzRCUyMkY2Ml9CeG4wcng3Z2czVlJZcjVoLTAlMjIlMjB2YWx1ZSUzRCUyMlN0ZXAlMjAyJTI2bHQlM0JiciUyNmd0JTNCJTI2bHQlM0JpJTI2Z3QlM0JEcnlpbmclMjZsdCUzQiUyRmklMjZndCUzQiUyMiUyMHN0eWxlJTNEJTIycm91bmRlZCUzRDElM0J3aGl0ZVNwYWNlJTNEd3JhcCUzQmh0bWwlM0QxJTNCZm9udFNpemUlM0QxMiUzQmdsYXNzJTNEMCUzQnN0cm9rZVdpZHRoJTNEMSUzQnNoYWRvdyUzRDAlM0JmaWxsQ29sb3IlM0QlMjNmOGNlY2MlM0JzdHJva2VDb2xvciUzRCUyM2I4NTQ1MCUzQiUyMiUyMHZlcnRleCUzRCUyMjElMjIlMjBwYXJlbnQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0xJTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhHZW9tZXRyeSUyMHglM0QlMjIyODAlMjIlMjB5JTNEJTIyLTIzMCUyMiUyMHdpZHRoJTNEJTIyMTIwJTIyJTIwaGVpZ2h0JTNEJTIyNDAlMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC0zJTIyJTIwdmFsdWUlM0QlMjJTdGVwJTIwMyUyNmx0JTNCYnIlMjZndCUzQiUyNmx0JTNCaSUyNmd0JTNCUGFydGljbGUlMjBTaXplJTIwUmVkdWN0aW9uJTI2bHQlM0IlMkZpJTI2Z3QlM0IlMjIlMjBzdHlsZSUzRCUyMnJvdW5kZWQlM0QxJTNCd2hpdGVTcGFjZSUzRHdyYXAlM0JodG1sJTNEMSUzQmZvbnRTaXplJTNEMTIlM0JnbGFzcyUzRDAlM0JzdHJva2VXaWR0aCUzRDElM0JzaGFkb3clM0QwJTNCZmlsbENvbG9yJTNEJTIzZjhjZWNjJTNCc3Ryb2tlQ29sb3IlM0QlMjNiODU0NTAlM0IlMjIlMjB2ZXJ0ZXglM0QlMjIxJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214R2VvbWV0cnklMjB4JTNEJTIyNDQwJTIyJTIweSUzRCUyMi0yMzAlMjIlMjB3aWR0aCUzRCUyMjE5NC41JTIyJTIwaGVpZ2h0JTNEJTIyNDAlMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC01JTIyJTIwdmFsdWUlM0QlMjIlMjIlMjBzdHlsZSUzRCUyMmVuZEFycm93JTNEY2xhc3NpYyUzQmh0bWwlM0QxJTNCcm91bmRlZCUzRDAlM0JleGl0WCUzRDElM0JleGl0WSUzRDAuNSUzQmV4aXREeCUzRDAlM0JleGl0RHklM0QwJTNCZW50cnlYJTNEMCUzQmVudHJ5WSUzRDAuNSUzQmVudHJ5RHglM0QwJTNCZW50cnlEeSUzRDAlM0IlMjIlMjBlZGdlJTNEJTIyMSUyMiUyMHBhcmVudCUzRCUyMldJeVdsTGs2R0pRc3FhVUJLVE5WLTElMjIlMjBzb3VyY2UlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC0wJTIyJTIwdGFyZ2V0JTNEJTIyRjYyX0J4bjByeDdnZzNWUllyNWgtMyUyMiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214R2VvbWV0cnklMjB3aWR0aCUzRCUyMjUwJTIyJTIwaGVpZ2h0JTNEJTIyNTAlMjIlMjByZWxhdGl2ZSUzRCUyMjElMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhQb2ludCUyMHglM0QlMjIzMTYlMjIlMjB5JTNEJTIyLTE5MCUyMiUyMGFzJTNEJTIyc291cmNlUG9pbnQlMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteFBvaW50JTIweCUzRCUyMjMwNiUyMiUyMHklM0QlMjItODAlMjIlMjBhcyUzRCUyMnRhcmdldFBvaW50JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhHZW9tZXRyeSUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQyUyRm14Q2VsbCUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUzQyUyRnJvb3QlM0UlMEElMjAlMjAlMjAlMjAlM0MlMkZteEdyYXBoTW9kZWwlM0UlMEElMjAlMjAlM0MlMkZkaWFncmFtJTNFJTBBJTNDJTJGbXhmaWxlJTNFJTBBC+1vsQAAD/tJREFUeF7tXX1wVNUVPxuZRIdIFFtGsQ5hUKoOrTotI8g4lPJVQzthSlAEitriQJXiV0FwwGmFARyrAUSFqq2mfCnRAS0JBigKQ8NUBdJGaxzRZBxCZICSDwzZsNA5F856cn1vebv79u29u2f/2mTfO+/e3/m983733PPuDQH7VI0rLsrp3v2h0+HwoNOnTuXz3+S7+QjkdOvWlpObu+f0iROlo97YVGF+i7u2UPhnm8e6tlf4Z7f/pPVZgkAoFOmWm/dlpOPkK5ETHaVFlZUt1PMQfdk+aULZBXm5xYW3Du3Rs18/yM0XPWAbPcJtbXDswAGo3/VeS6QjvGn4mvVTbOmD8M8WT7m3U/hnvw+lB5mPwJlIBFqbmuBQzf72wx/VdnR2dt5RVL6xCnuuBAEG44I+fYoHlIzvkflwZEcPa8s3tDQ3NFghCoR/mcdJ4V/m+VR6lHkIHKmrg9o3yyMhOHPz6A0bPwxhmja3oGDdoBkzRQxkmL/3rFjeEm5uvtPk6QPhX4aRjnVH+Je5vpWeZQ4CjXv3wuc73/1gRNnagaFtUyZuvXrY8BGX33BD5vRQeqIQaKqpgc92bN82omztSFMhEf6Z6pnk2yX8Sx5DsSAIBIFA9bPLWsNtrcNCVRNKWgfdNyNfagaCgD3Ya+Cc7p7nV7SNWl9+cbBX9n414Z93rGw7Uvhnm8ekvdmKQF3F5vZDNftmh7aUjD3zk8fmZSsOGd/vdxcthJ+Vb4wWj5rWYeGfaR7xtz3CP3/xFGuCQCoQqN+1Exp27fyDCIJUoGuQTQnIBjkjC5si/MtCp0uXrUPAWkHwaX0DTJ4zF/796acK9KnjfglP/f4RuCgvD/C3hatWwdI5j0LPggJfnbLoxZeg75VXwp1Ft/lqN9XGJCD7i3CQ/Gvv6IBZf3oaXnrjzW9x3d9epc6a8C912JpkGePjEy+sjDZpx19ehsE3nq1L8zt28ntw5ODB8Oqihb7He5OwDaItVgoCIsKyOY92IVvj4cNKFHx5qCklgoDI/teFC0QQ+MxOm6YMgubfuopKhTaKUBIHQ266ySoOiiDw+YYx0BzGR4rBNDDDQRvFaT8FAd4HC1augruLi6F/YR/Ae2T3vn3RQaGB8FjRJCsFQfX+GqU2uSLEIP3wU0/B49OnK6Jsra4GUo1H/nc8mk3gShLtrNm8GXrk58Mzr5ZFj9ezChSEe/fqpZwqGQL/uW2TIAiafzraNgY/EQT+3zMmWXQTqhinKWbeM2+++k4DKp5NoP+RnZuuuxZWvV6uMsBeBmCpzAqbhHOq22KlIDjW3Ax3PTYPvjp6FFYvWawUIv9wcuD/8djH7p2qsglcxe7/7ycw7Ne/6UJQPB6Pdfv4qXJT7VxuXwKyf2ink3+Uej0fT/3rrT+WhH/+4GiyFRSq+NB//LfTHWMoj51c1GJGlzIJN153rZoea2g8pAZ8OJjDgd4zs2Z9K85zLGwUySb60kpBQEASAfHvH/bvHxUHXBDUfVHfJZvg9Te32gMRBKmhsU0ZgnTyzyk7kRqP+GtVBIG/eJpqjcQyZmjxw8UBxc6xw3+qHvp82svLb051W/x6vF7BVHxMb5fVgoCDywMlqkoqKkRBgFkA/iHxcPT4cTVlEE8xogiC1FDaRkEQNP+Q4w8sedIxK5Yar/hnVQSBf1jaYkmfRtAf+lQkS/1B8fDQlF8psTBpzJi4ihFJGFAm2BaMTGunlYKAF1kRoEiIB5c8CfOmTVP/4oKAP/TdgjhmBLyMvkQQpIbCNgmCdPAPr7l2c4W1ldQiCFJz35hiFePv4yuegydm3N+l0h95+8XBg2oKQRcE/KFP/dBFhNciWq/HmYKXqe2wUhBQASGfV+IBk2cIEHheQ8CPo+wBpZqoAEZqCIKnq02CIGj+eRGqwXssviuKIIgPLxuP1uMnjdonjilSb8S41RC0nzypYjQeR9MJ2H96Y8yphoAPALGGzOmetBHDdLfZSkGAoOnvgfO3B4iIeBwVptCaBbzWAAPtC6+9pnzw+jtVXdYycHOMZAgSpuwjAPBnAGh1smCTIAiaf/q73Xh9vu5Gwh4J8EQDBEFG8S9A18V1KZ2r/A0BqvlyesuAag34G120noFbbYD+DJAagrhc5XiwtYIg+a6DmiJwm07ww75JNgwIyO0AcAEAPI1rlOjCwDZB4IdvhX9+oOjZhvDPM1TpO5AEgdN0QvpalT1XFkHAigoz2e0GCIIHAGAJAOQAwBkAKOXCQARBXibTD4R/Ge1e3zongsA3KBMylNWCICHELD3JgICMyB0BgMvOQRjmwmBLydgW2VzLUnJ5aLbwzwNIcoggkGYERBCk2QFBXf5cQA7qcvFcpxMA3tpSMnacCIJ4YLPr2KmTJ8Pqjz8xsdHCPxO9Im1KCwIiCNICe/AXlRFa8JjLFb9BQPgnbBAEzEdABIH5PvKlhQYEZKwhWHyusFBqCHzxqj1GhH/2+Epamr0IWC0I8BWXjdv/8a2V2/D1ltKyv6n/f+fSS2Dl6xvUCli4A5fTB48v7N07ujJWJtLBgICccVXe+itWiW7BKvwL5I6zjn/6a3WEUiKv1+EbLfWNjWo9AP7dDXnk9rCBA+OKibG2BMdXwc8Xh72ywA0Xtz0UYtlNdlOkeHH12sd0HWetIKDtL3FjjPnTp0U3vqAFK348YABM/vkY2R/7HLMMEAQZ9R6408psmbCAUKoCkfAvfmSRTzvef7/LRkGJvKoab+W+vrWwl5brCwXhOV4WevNiWz/mfCuF6pvdxbpGIniSvXhxTaSvQZ9jrSBAZffKpk0Kr18MHRpVskiWXj17Qn3jQZg4ZozKIPAPKmS+gtboIbdEl9zEFQ7RZr+rvgf3L1zUZfEXcj6uv41KFLdAxo/ThhtBO9HL9QwIyDGbadtrh8Q/FKOUeeIB4vt9CxWv+hcWwuq3/654gr/TKpgUiObeOxUWv/iSWvJV+OeFyak5xkT+OY3SOe9ol0DcIpgvuEZiFblX9tbbcF3fvrChqkod8/ITf4R1lZVwd3GxGkQhD2mvF1rsClcOpGWIL7rwQrW3AO07EGuRIIyd/H7go+93dv9TOQ4zsXxvGX1TOlpALla2zQkX/eHs1C+8T3kcx/72yM+HH1xzjbo/udDQRZFub8HvZsD8Z1coXLziitcnkYdY4MJLiWQ1UnMHnLVqrSDgwOLDmR70SOTRQ4ZA29dfR5fLxNQXBWgMvJi6wg8GZ36DOW2HjOfSlpy0OxetuJVI6i6VzoxlWwSBv8g7jd5oVIScueySS9SWrjhVRWlaGu3xYIPnUCAV/vnro3ismSYInEbpfL1+HMjQ3i30YCd+UUqduMdjHH/Y6zvB0oMWubtl9264t2ScEgO9e/WKxkraI0bfDZbaRtsW6787PcT5PgfU5mVzHlWDO/4b96Nb9oJn57BffBMwt50UeRzHGL9g5aqoUOIZwFg40b17PlzpeRPrmvHwNVXHWisISM0RMHytbNxMgx7k3Ml4TsXOXVBwcX50h0Me2PVUFJEYr8FXNHRKj6XKQX7ZFUHgF5Jn7bjNsbpxRheeFLyFf/76JVFrpgkCfRth6hct+4u/4+idslOcR3oanP9GPJx1z91qhOu0IiDFQRzNI59x+Xd8wHuZSqAHHh/5O52n1xTo0wtOGTjEwA0XyihQRoNvrUz9x2eCWxzHWjO+OZMXnLziyvuCtW1Um+EFz0T5nOh51goCCrxYKIMCoGTkSLXD4eIHH4Tn1q9XSo+PvvDGcdoAg+w4KURS4B9+/LGyRdMDbjt7JeqEIM4TQeAfym43MheKbpyZO3VqlJ84shP++eeXZCyZJgjcMlDUR57C1sWCPrDhf9N3PcPAseOx9Z5587vAyh/0sfDmW3XrcRjvH3wwTr99fFRo8GkJsuu0XwfGcMxezJw0UR2mFwW6CQanaV49C8DrNahYMBZObrjquz46TQ+iwEq2oDEZvruda6Ug4AH56PHjqvAGpw1Q0fKpAUz18DQtkY5UNrfjpBApPUbzXyQIznezpsJRydoUQZAsgt+c7zZ6oTQnpmp5ZgrPJK5hfcpXR4+pFKzwzz+fJGvJNEHgVDhHfdTny/nf+sBGP5Ye9jxO8vQ+56Quat0wdivMo1Q9xmWn6TIq/otnpOyEC88uxBqs6efydlOtGcV4Lzjh84QyLLGOJxx+dP310elBqicwbS8dKwWBXlizfM0aVbyFc144D0vk4wQg0mAmwWnehwq6qCjGLQXHt+q0paAQb2QRBMk+Mr453636m9KreKQ+SqDA/K//1EZfk+XBS/jnn38SsWSaIIj12p9TAR3NmesDG561uuqKy6NCFb/zBxrGyt379gEvcsUBFX9gub01QKNyFLk4/08jd9q2mAuLWFNtvBaMb1nvlL2g6+hZApoyoAc1zwrj4JH6Q3Ec7WC7ebv4a+uxcJpbuhTmTZsGsXDlmRIavFJhcSzRlwiH/TjHSkGgz91g8RYvRkFgqKYA52tQIDQePhytG3BSbLpCdKonwKpQnKvq0/sKx7k3PxySKhsiCPxDluZJuUWe3nTLIBDvSEjy44R//vknEUsmCQIvI2Y+ZXD76FGqWn7mpEmq67zanxf7LZ0zW6XqsbCaUtZU1U/85QMqtMXX2ohVEa+vDcCnFnixIl2PfMRrIlAEbK2uVj85FWy74cKLLfHe4m3RpzioPxjHR94yGL576aXRol96++Hhu6aoNtDgkNsjnPB3FFRYRKnjyqctnHAgMRNL9CXCYT/OsVIQ+NHxRG3YWD8gGYJEve3feX7xxi87/vXMmyURpN5wkqMEgXQiIILAA/pcJbupVw9m0nqIBOT0wU/8SfQ1VeFf6n1nUoYg9b2VKwgCzgiIIMgSZoggyBJHG9pN4Z+hjpFmCQIMgaggqJpQ0jrovhn5ufn5AlCGIRBua4M9z69oG7W+/GJTuyb8M9UzybdL+Jc8hmJBEAgCgbqKze2HavbNDm2bMnHr1cOGj7j8hrNVovLJHASaamrgsx3bt40oWzvS1F4J/0z1TPLtEv4lj6FYEASCQKD62WWt4bbWYaGqccVFuQUF6wbNmNkjiAvLNYJDYM+K5S3h5uY7R72xqSK4q8Z3JeFffHjZdLTwzyZvSVuzFYHGvXvh853vfjCibO3AEIKwfdKEsoI+fYoHlIwXUZAhrKgt39DS3NCwafia9WffpTH4I/wz2DkJNk34lyBwcpogECACR+rqoPbN8kgIztw8esPGD5UgIFFwQV5uceGtQ3v07NcPpKYgQK/4dCmcsz124ADU73qvJdIRtkIMCP98cr4BZoR/BjhBmiAInAeBM5EItDY1waGa/e2HP6rt6OzsvKOofGMVnhYVBPgHpm9zund/6HQ4POj0qVNSZWgZtXK6dWvLyc3dc/rEiVKTpwncYBX+WUY4rbnCP7v9J63PEgRCoUi33LwvIx0nX4mc6CgtqqxsoZ7/H1ownqsxbrJcAAAAAElFTkSuQmCC&quot;/>
                    </attachment>
                </content>
            </DocumentReference>
        </resource>
    </entry>
    <!-- Section 5.1 - Manufacturing Process Overview - Process Flow Diagram -->
    <entry>
        <fullUrl value=&quot;urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee&quot;/>
        <resource>
            <DocumentReference>
                <id value=&quot;DocumentReference-image&quot;/>
                <status value=&quot;current&quot;/>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;/>
                    </attachment>
                </content>
            </DocumentReference>
        </resource>
    </entry>
    <!-- MedicinalProductDefinition - the main resource in any product scenario -->
    <entry>
        <fullUrl value=&quot;urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d5&quot;/>
        <resource>
            <!-- Section 1.1 - DP Identification -->
            <MedicinalProductDefinition>
                <id value=&quot;medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                <description value=&quot;Textual description of the product&quot;/>
                <combinedPharmaceuticalDoseForm>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;10225000&quot;/>
                        <display value=&quot;Gastro-resistant tablet&quot;/>
                    </coding>
                </combinedPharmaceuticalDoseForm>
                <route>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;20053000&quot;/>
                        <display value=&quot;Oral use&quot;/>
                    </coding>
                </route>
                <name>
                    <productName value=&quot;Stelbat Tablets, 20mg&quot;/>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>
                    </type>
                    <part>
                        <part value=&quot;20mg&quot;/>
                        <type>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/medicinal-product-name-part-type&quot;/>
                                <code value=&quot;StrengthPart&quot;/>
                                <display value=&quot;Strength part&quot;/>
                            </coding>
                        </type>
                    </part>
                </name>
            </MedicinalProductDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d6&quot;/>
        <resource>
            <Ingredient>
                <id value=&quot;productIngredient&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072072&quot;/>
                        <display value=&quot;Active&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                        </reference>
                    </code>
                </substance>
            </Ingredient>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152&quot;/>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;Stelbatolol&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Stelbatolol&quot;/>
                </name>
            </SubstanceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:c458791f-7cb8-428e-83f7-8a205f821113&quot;/>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;StelbatololGranules&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;/>
                </meta>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;/>
                </name>
            </SubstanceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d&quot;/>
        <resource>
            <Organization>
                <id value=&quot;substance-manufacturer&quot;/>
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>
                </identifier>
                <active value=&quot;true&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>
                </type>
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;/>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>
                    </address>
                </contact>
            </Organization>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:8d61736c-a6e3-8301-659f-17da402e012a&quot;/>
        <resource>
            <Organization>
                <id value=&quot;manufacturerProcessingMaterial&quot;/>
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3010027650&quot;/>
                </identifier>
                <active value=&quot;true&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-product-manufacture&quot;/>
                        <display value=&quot;Drug Product Manufacture&quot;/>
                    </coding>
                </type>
                <name value=&quot;AAA Pharmaceutical, Inc.&quot;/>
                <contact>
                    <address>
                        <line value=&quot;681 Main Street&quot;/>
                        <city value=&quot;Lumberton&quot;/>
                        <state value=&quot;New Jersey&quot;/>
                        <postalCode value=&quot;08048&quot;/>
                        <country value=&quot;USA&quot;/>
                    </address>
                </contact>
            </Organization>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:c458791f-7cb8-428e-83f7-8a205f821153&quot;/>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;startingMaterial&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Stelbatosubstance&quot;/>
                </name>
            </SubstanceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:c458791f-7cb8-428e-83f7-8a205f821154&quot;/>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;StelbatololAqueousSolution&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;/>
                </meta>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;/>
                </name>
            </SubstanceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:c458791f-7cb8-428e-83f7-8a205f821155&quot;/>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;processingMaterial&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/manufacturerProcessingMaterial&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Processohol&quot;/>
                </name>
            </SubstanceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:82a39a18-91cf-a29d-76c1-a9e8bad9494d&quot;/>
        <resource>
            <DeviceDefinition>
                <id value=&quot;mixing-vessel&quot;/>
                <deviceName>
                    <name value=&quot;Mixing Vessel&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;mixing-vessel&quot;/>
                            <display value=&quot;Mixing Vessel&quot;/>
                        </coding>
                    </type>
                </classification>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>
                </property>
            </DeviceDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:82a39a18-91cf-b29d-76c1-a9e8bad9494d&quot;/>
        <resource>
            <DeviceDefinition>
                <id value=&quot;receiving-tank&quot;/>
                <deviceName>
                    <name value=&quot;Receiving Tank&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;receiving-tank&quot;/>
                            <display value=&quot;Receiving Tank&quot;/>
                        </coding>
                    </type>
                </classification>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1200&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>
                </property>
            </DeviceDefinition>
        </resource>
    </entry>" id="Bundle-bundle-product-manufacturing-pq-ex1">Bundle</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/bundle.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/bundle.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/bundle.html#tt-uml">R6</a>]</span><div class="debugOff">id: bundle-product-manufacturing-pq-ex1</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <meta>
        <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-product-manufacturing-pq&quot;>">Profile: </span><span title="
<Bundle>
    <meta>
        <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-product-manufacturing-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-product-manufacturing-pq</span></div>
<div><span title="
<Bundle>
    ...
    <type value=&quot;collection&quot;>">Type: </span><span title="
<Bundle>
    ...
    <type value=&quot;collection&quot;>"><span>collection</span></span></div>
</div>
</div>
<div>
<div class="indent plan summaryUnit"><a class="plainLink"><span class="bold" title="PlanDefinition (id: manufacturingProcess-unlinked)(fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265a)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq 

<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <id value=&quot;manufacturingProcess-unlinked&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq&quot;/>
                </meta>
                <extension url=&quot;http://nprogram.co.uk/fhir/extension/viewer/tabulateEquipment&quot;>
                    <valueBoolean value=&quot;true&quot;/>
                </extension>
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-plan-document-reference-pq&quot;>
                    <valueReference>
                        <!-- Process flow diagram -->
                        <!-- or could be a Binary -->
                        <reference value=&quot;DocumentReference/documentreference-drug-pq-process-flow-diagram&quot;/>
                    </valueReference>
                </extension>
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-history-of-process-pq&quot;>
                    <valueMarkdown value=&quot;This can be text about the history&quot;/>
                </extension>
                <url value=&quot;http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a&quot;/>
                <title value=&quot;Process 1.0&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/plan-definition-type&quot;/>
                        <code value=&quot;workflow-definition&quot;/>
                        <display value=&quot;Workflow Definition&quot;/>
                    </coding>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-plan-type&quot;/>
                        <code value=&quot;manufacturing-process&quot;/>
                        <display value=&quot;Manufacturing Process&quot;/>
                    </coding>
                </type>
                <status value=&quot;active&quot;/>
                <subjectReference>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </subjectReference>
                <description value=&quot;Narrative description of manufacturing process (5)&quot;/>
                <goal id=&quot;goal-control-pH&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - pH&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>
                            </coding>
                            <text value=&quot;pH must be in range 6.9 to 7.1&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </low>
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <goal id=&quot;goal-control-water-content&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Water Content&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>
                            </coding>
                            <text value=&quot;Under 2%&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Particle Size&quot;/>
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>
                            </coding>
                            <text value=&quot;Under 200 microns&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/mixing-vessel&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>
                        </role>
                    </option>
                </actor>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/receiving-tank&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>
                        </role>
                    </option>
                </actor>
                <!-- outer action is the whole thing, if needed -->
                <!-- step 1 mixing -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;1&quot;/>
                    <description value=&quot;Mixing of ingredients&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>
                        </coding>
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-pH&quot;/>
                    <!--goalId value=&quot;goal-control-temp&quot;/-->
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/mixer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/startingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/processingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;processing material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <!--action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlPH&quot;/>
                        </action>
                        <action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlTemperature&quot;/>
                        </action-->
                </action>
                <!-- step 2 drying -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <!-- todo want a range here -->
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;2&quot;/>
                    <description value=&quot;Drying using a heater&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-water-content&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/dryer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                </action>
                <!-- step 3 particle size -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;3&quot;/>
                    <description value=&quot;Particle Size Reduction by using a rotating impeller&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-particle-size&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/devicedefinition-drug-pq-ex1&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                </action>" id="PlanDefinition-manufacturingProcess-unlinked">Plan</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/plandefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/plandefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/plandefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: manufacturingProcess-unlinked</div>
<div class="debugOff"> fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265a</div>
<div class="debugOff">url (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <title value=&quot;Process 1.0&quot;>">Title: </span><span>Process 1.0</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <description value=&quot;Narrative description of manufacturing process (5)&quot;>">Description: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <description value=&quot;Narrative description of manufacturing process (5)&quot;>">Narrative description of manufacturing process (5)</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/plan-definition-type&quot;/>
                        <code value=&quot;workflow-definition&quot;/>
                        <display value=&quot;Workflow Definition&quot;/>
                    </coding>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-plan-type&quot;/>
                        <code value=&quot;manufacturing-process&quot;/>
                        <display value=&quot;Manufacturing Process&quot;/>
                    </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/plan-definition-type&quot;/>
                        <code value=&quot;workflow-definition&quot;/>
                        <display value=&quot;Workflow Definition&quot;/>">Workflow Definition<span class="greyOff"> [workflow-definition]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/plan-definition-type)</span></span>, <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <type>
                    ...
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-plan-type&quot;/>
                        <code value=&quot;manufacturing-process&quot;/>
                        <display value=&quot;Manufacturing Process&quot;/>">Manufacturing Process<span class="greyOff"> [manufacturing-process]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-plan-type)</span></span></div>
<div class="summaryHiddenOff">
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <status value=&quot;active&quot;>">Status: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <status value=&quot;active&quot;>"><span>active</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-history-of-process-pq&quot;>
                    <valueMarkdown value=&quot;This can be text about the history&quot;/>">History: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-history-of-process-pq&quot;>
                    <valueMarkdown value=&quot;This can be text about the history&quot;/>"><span>This can be text about the history</span></span></div>
</div>
<div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <id value=&quot;manufacturingProcess-unlinked&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/PlanDefinition-drug-pq&quot;/>
                </meta>
                <extension url=&quot;http://nprogram.co.uk/fhir/extension/viewer/tabulateEquipment&quot;>
                    <valueBoolean value=&quot;true&quot;/>
                </extension>
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-plan-document-reference-pq&quot;>
                    <valueReference>
                        <!-- Process flow diagram -->
                        <!-- or could be a Binary -->
                        <reference value=&quot;DocumentReference/documentreference-drug-pq-process-flow-diagram&quot;/>
                    </valueReference>
                </extension>
                <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-history-of-process-pq&quot;>
                    <valueMarkdown value=&quot;This can be text about the history&quot;/>
                </extension>
                <url value=&quot;http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a&quot;/>
                <title value=&quot;Process 1.0&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/plan-definition-type&quot;/>
                        <code value=&quot;workflow-definition&quot;/>
                        <display value=&quot;Workflow Definition&quot;/>
                    </coding>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-plan-type&quot;/>
                        <code value=&quot;manufacturing-process&quot;/>
                        <display value=&quot;Manufacturing Process&quot;/>
                    </coding>
                </type>
                <status value=&quot;active&quot;/>
                <subjectReference>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </subjectReference>
                <description value=&quot;Narrative description of manufacturing process (5)&quot;/>
                <goal id=&quot;goal-control-pH&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - pH&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>
                            </coding>
                            <text value=&quot;pH must be in range 6.9 to 7.1&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </low>
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <goal id=&quot;goal-control-water-content&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Water Content&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>
                            </coding>
                            <text value=&quot;Under 2%&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Particle Size&quot;/>
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>
                            </coding>
                            <text value=&quot;Under 200 microns&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>
                            </high>
                        </detailRange>
                    </target>
                </goal>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/mixing-vessel&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>
                        </role>
                    </option>
                </actor>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/receiving-tank&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>
                        </role>
                    </option>
                </actor>
                <!-- outer action is the whole thing, if needed -->
                <!-- step 1 mixing -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;1&quot;/>
                    <description value=&quot;Mixing of ingredients&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>
                        </coding>
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-pH&quot;/>
                    <!--goalId value=&quot;goal-control-temp&quot;/-->
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/mixer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/startingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/processingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;processing material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <!--action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlPH&quot;/>
                        </action>
                        <action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlTemperature&quot;/>
                        </action-->
                </action>
                <!-- step 2 drying -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <!-- todo want a range here -->
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;2&quot;/>
                    <description value=&quot;Drying using a heater&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-water-content&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/dryer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                </action>
                <!-- step 3 particle size -->
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;3&quot;/>
                    <description value=&quot;Particle Size Reduction by using a rotating impeller&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-particle-size&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/devicedefinition-drug-pq-ex1&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                </action>">Subject</span><div class="indent mpd summaryUnit"><a class="plainLink"><span class="bold" title="MedicinalProductDefinition (id: medicinalproductdefinition-drug-product-dxpq-ex1)(fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d5)

<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <id value=&quot;medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                <description value=&quot;Textual description of the product&quot;/>
                <combinedPharmaceuticalDoseForm>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;10225000&quot;/>
                        <display value=&quot;Gastro-resistant tablet&quot;/>
                    </coding>
                </combinedPharmaceuticalDoseForm>
                <route>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;20053000&quot;/>
                        <display value=&quot;Oral use&quot;/>
                    </coding>
                </route>
                <name>
                    <productName value=&quot;Stelbat Tablets, 20mg&quot;/>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>
                    </type>
                    <part>
                        <part value=&quot;20mg&quot;/>
                        <type>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/medicinal-product-name-part-type&quot;/>
                                <code value=&quot;StrengthPart&quot;/>
                                <display value=&quot;Strength part&quot;/>
                            </coding>
                        </type>
                    </part>
                </name>" id="MedicinalProductDefinition-medicinalproductdefinition-drug-product-dxpq-ex1">Product</span></a><span class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/medicinalproductdefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/medicinalproductdefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/medicinalproductdefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: medicinalproductdefinition-drug-product-dxpq-ex1</div><div class="debugOff"> fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d5</div></span><div class="summaryHiddenOff"></div><span class="summaryShowsOff"><b> - </b></span><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                ...
                <name>
                    <productName value=&quot;Stelbat Tablets, 20mg&quot;/>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>
                    </type>
                    <part>
                        <part value=&quot;20mg&quot;/>
                        <type>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/medicinal-product-name-part-type&quot;/>
                                <code value=&quot;StrengthPart&quot;/>
                                <display value=&quot;Strength part&quot;/>
                            </coding>
                        </type>
                    </part>" class="bold"><span class="summaryHiddenOff">Name: </span><span>Stelbat Tablets, 20mg</span></span><div class="summaryHiddenOff"><div><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <name>
                    ...
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>">Name type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <name>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>">Proprietary<span class="greyOff"> [Proprietary]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example)</span></span></div><div title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <name>
                    ...
                    <part>
                        <part value=&quot;20mg&quot;/>
                        <type>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/medicinal-product-name-part-type&quot;/>
                                <code value=&quot;StrengthPart&quot;/>
                                <display value=&quot;Strength part&quot;/>
                            </coding>
                        </type>"><span>Strength name part: </span><span>20mg</span></div></div><div class="summaryHiddenOff"><div><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                ...
                <description value=&quot;Textual description of the product&quot;>">Description: </span><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                ...
                <description value=&quot;Textual description of the product&quot;>">Textual description of the product</span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                ...
                <route>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;20053000&quot;/>
                        <display value=&quot;Oral use&quot;/>
                    </coding>">Route of Administration: </span><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <route>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;20053000&quot;/>
                        <display value=&quot;Oral use&quot;/>">Oral use<span class="greyOff"> [20053000]</span><span class="greyOff"> (http://standardterms.edqm.eu)</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                ...
                <combinedPharmaceuticalDoseForm>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;10225000&quot;/>
                        <display value=&quot;Gastro-resistant tablet&quot;/>
                    </coding>">Dose Form (combination of all parts): </span><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <combinedPharmaceuticalDoseForm>
                    <coding>
                        <system value=&quot;http://standardterms.edqm.eu&quot;/>
                        <code value=&quot;10225000&quot;/>
                        <display value=&quot;Gastro-resistant tablet&quot;/>">Gastro-resistant tablet<span class="greyOff"> [10225000]</span><span class="greyOff"> (http://standardterms.edqm.eu)</span></span></div></div><div class="summaryHiddenOff"></div><div class="indent ing summaryUnit"><a class="plainLink"><span class="bold" title="Ingredient (id: productIngredient)(fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d6)

<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <id value=&quot;productIngredient&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072072&quot;/>
                        <display value=&quot;Active&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                        </reference>
                    </code>
                </substance>" id="Ingredient-productIngredient">Ingredient</span></a><span class="summaryShowsOff"> - <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072072&quot;/>
                        <display value=&quot;Active&quot;/>">Active<span class="greyOff"> [100000072072]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></span><div class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/ingredient.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/ingredient.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/ingredient.html#tt-uml">R6</a>]</span><div class="debugOff">id: productIngredient</div><div class="debugOff"> fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d6</div><div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <status value=&quot;active&quot;>">Status: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <status value=&quot;active&quot;>"><span>active</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072072&quot;/>
                        <display value=&quot;Active&quot;/>
                    </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072072&quot;/>
                        <display value=&quot;Active&quot;/>">Active<span class="greyOff"> [100000072072]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></div></div><div class="indent ingsub"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <substance>
                    <code>
                        <reference>
                            <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                        </reference>
                    </code>" class="summaryHiddenOff">Substance</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><div class="debugOff"><span>Found a parent (Ingredient/code, id: productIngredient fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d6)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: Stelbatolol)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152)

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;Stelbatolol&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Stelbatolol&quot;/>
                </name>" id="SubstanceDefinition-Stelbatolol">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: Stelbatolol</div><div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152</div><div class="summaryHiddenOff"><div class="indent sbddetails"><div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol&quot;>"><span>Stelbatolol</span></span></div></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"><div class="indent sbddetails2"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                ...
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>">Manufacturer</span><div class="indent org summaryUnit"><div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: Stelbatolol fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152)<br>which is linked to this by resource.id</span></div><div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: startingMaterial fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821153)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="Organization (id: substance-manufacturer)(fullUrl: urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d)

<Bundle>
    <entry>
        <resource>
            <Organization>
                <id value=&quot;substance-manufacturer&quot;/>
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>
                </identifier>
                <active value=&quot;true&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>
                </type>
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;/>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>
                    </address>
                </contact>" id="Organization-substance-manufacturer">Organization</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/organization.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/organization.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/organization.html#tt-uml">R6</a>]</span><div class="debugOff">id: substance-manufacturer</div><div class="debugOff"> fullUrl: urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d</div><span class="summaryShowsOff"> - AAA Molybdenum Products, Inc.</span><div class="summaryHiddenOff"><div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>">Identifier: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>">3003040516<span class="greyOff"> (urn:oid:2.16.840.1.113883.4.82)</span></span></div><div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>">Active: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>"><span>true</span></span></div></div><div class="summaryHiddenOff"><div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;>">Name: </span><span>AAA Molybdenum Products, Inc.</span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>">Drug Substance Manufacture<span class="greyOff"> [drug-substance-manufacture]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type)</span></span></div><div class="indent org2">
					Contact
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>">Address: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;>">7233 W 116th Pl</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <line value=&quot;Ste C&quot;>">Ste C</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <city value=&quot;Broomfield&quot;>">Broomfield</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <state value=&quot;Colorado&quot;>">Colorado</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <postalCode value=&quot;80020&quot;>">80020</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <country value=&quot;USA&quot;>">USA</span></div></div></div></div></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div class="summaryHiddenOff"></div></div><div class="summaryHiddenOff"></div></div><div></div></div></span><div class="indent summaryUnit"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/mixing-vessel&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>
                        </role>
                    </option>"><span>Actor</span><span class="summaryHiddenOff"></span></span><div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/mixing-vessel&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;mixing-vessel&quot;/>
                                <display value=&quot;Mixing Vessel&quot;/>">Mixing Vessel<span class="greyOff"> [mixing-vessel]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class)</span></span></span></div>
<div class="indent devd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/typeReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DeviceDefinition (id: mixing-vessel)(fullUrl: urn:uuid:82a39a18-91cf-a29d-76c1-a9e8bad9494d)

<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <id value=&quot;mixing-vessel&quot;/>
                <deviceName>
                    <name value=&quot;Mixing Vessel&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;mixing-vessel&quot;/>
                            <display value=&quot;Mixing Vessel&quot;/>
                        </coding>
                    </type>
                </classification>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>
                </property>" id="DeviceDefinition-mixing-vessel">Device</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/devicedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/devicedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/devicedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: mixing-vessel</div>
<div class="debugOff"> fullUrl: urn:uuid:82a39a18-91cf-a29d-76c1-a9e8bad9494d</div>
<div class="summaryHiddenOff"></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <deviceName>
                    <name value=&quot;Mixing Vessel&quot;/>
                    <type value=&quot;registered-name&quot;/>">Name: </span><span>Mixing Vessel</span><span> (name type: registered-name)</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;mixing-vessel&quot;/>
                            <display value=&quot;Mixing Vessel&quot;/>
                        </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;mixing-vessel&quot;/>
                            <display value=&quot;Mixing Vessel&quot;/>">Mixing Vessel<span class="greyOff"> [mixing-vessel]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example)</span></span></div>
<div class="summaryHiddenOff">
<div class="summaryHiddenOff">
<div class="indent devdl2"><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>">Property</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>">Type: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->">Capacity<span class="greyOff"> [Capacity]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/device-property)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>">Value: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>">1000 litres</span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="indent summaryUnit"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/receiving-tank&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>
                        </role>
                    </option>"><span>Actor</span><span class="summaryHiddenOff"></span></span><div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        <typeReference>
                            <reference value=&quot;DeviceDefinition/receiving-tank&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <actor>
                    <option>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;receiving-vessel&quot;/>
                                <display value=&quot;Receiving Vessel&quot;/>">Receiving Vessel<span class="greyOff"> [receiving-vessel]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class)</span></span></span></div>
<div class="indent devd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/typeReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DeviceDefinition (id: receiving-tank)(fullUrl: urn:uuid:82a39a18-91cf-b29d-76c1-a9e8bad9494d)

<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <id value=&quot;receiving-tank&quot;/>
                <deviceName>
                    <name value=&quot;Receiving Tank&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;receiving-tank&quot;/>
                            <display value=&quot;Receiving Tank&quot;/>
                        </coding>
                    </type>
                </classification>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1200&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>
                </property>" id="DeviceDefinition-receiving-tank">Device</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/devicedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/devicedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/devicedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: receiving-tank</div>
<div class="debugOff"> fullUrl: urn:uuid:82a39a18-91cf-b29d-76c1-a9e8bad9494d</div>
<div class="summaryHiddenOff"></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <deviceName>
                    <name value=&quot;Receiving Tank&quot;/>
                    <type value=&quot;registered-name&quot;/>">Name: </span><span>Receiving Tank</span><span> (name type: registered-name)</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;receiving-tank&quot;/>
                            <display value=&quot;Receiving Tank&quot;/>
                        </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <classification>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example&quot;/>
                            <code value=&quot;receiving-tank&quot;/>
                            <display value=&quot;Receiving Tank&quot;/>">Receiving Tank<span class="greyOff"> [receiving-tank]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-deviceType-pq-example)</span></span></div>
<div class="summaryHiddenOff">
<div class="summaryHiddenOff">
<div class="indent devdl2"><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1200&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>">Property</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->
                        </coding>">Type: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Capacity&quot;/>
                            <display value=&quot;Capacity&quot;/>
                            <!-- seems a little different to &quot;maximum capacity -->">Capacity<span class="greyOff"> [Capacity]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/device-property)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1200&quot;/>
                        <unit value=&quot;litres&quot;/>">Value: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1200&quot;/>
                        <unit value=&quot;litres&quot;/>">1200 litres</span></span></div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DocumentReference (id: documentreference-drug-pq-process-flow-diagram)(fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41feb)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DocumentReference-drug-pq 

<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <id value=&quot;documentreference-drug-pq-process-flow-diagram&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DocumentReference-drug-pq&quot;/>
                </meta>
                <identifier>
                    <system value=&quot;http://example.org/fhir/identifier/document&quot;/>
                    <value value=&quot;FLOW-001&quot;/>
                </identifier>
                <status value=&quot;current&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/diagram-type&quot;/>
                        <code value=&quot;ProcessFlowDiagram&quot;/>
                        <display value=&quot;Process Flow Diagram&quot;/>
                    </coding>
                </type>
                <content>
                    <attachment>
                        <contentType value=&quot;image/x-png&quot;/>
                        <data value=&quot;iVBORw0KGgoAAAANSUhEUgAAAgQAAAApCAYAAABKrzFXAAAAAXNSR0IArs4c6QAAEjl0RVh0bXhmaWxlACUzQ214ZmlsZSUyMGhvc3QlM0QlMjJFbGVjdHJvbiUyMiUyMG1vZGlmaWVkJTNEJTIyMjAyMy0wNy0wNlQxMyUzQTA4JTNBMDguNDgzWiUyMiUyMGFnZW50JTNEJTIyTW96aWxsYSUyRjUuMCUyMChXaW5kb3dzJTIwTlQlMjAxMC4wJTNCJTIwV2luNjQlM0IlMjB4NjQpJTIwQXBwbGVXZWJLaXQlMkY1MzcuMzYlMjAoS0hUTUwlMkMlMjBsaWtlJTIwR2Vja28pJTIwZHJhdy5pbyUyRjIxLjYuMSUyMENocm9tZSUyRjExMi4wLjU2MTUuMjA0JTIwRWxlY3Ryb24lMkYyNC42LjElMjBTYWZhcmklMkY1MzcuMzYlMjIlMjBldGFnJTNEJTIyNkMxTlFraVpHaXdVNTVadFBEMUQlMjIlMjB2ZXJzaW9uJTNEJTIyMjEuNi4xJTIyJTIwdHlwZSUzRCUyMmRldmljZSUyMiUzRSUwQSUyMCUyMCUzQ2RpYWdyYW0lMjBpZCUzRCUyMkM1UkJzNDNvRGEtS2R6WmVOdHV5JTIyJTIwbmFtZSUzRCUyMlBhZ2UtMSUyMiUzRSUwQSUyMCUyMCUyMCUyMCUzQ214R3JhcGhNb2RlbCUyMGR4JTNEJTIyMTAzNiUyMiUyMGR5JTNEJTIyMTc4MyUyMiUyMGdyaWQlM0QlMjIxJTIyJTIwZ3JpZFNpemUlM0QlMjIxMCUyMiUyMGd1aWRlcyUzRCUyMjElMjIlMjB0b29sdGlwcyUzRCUyMjElMjIlMjBjb25uZWN0JTNEJTIyMSUyMiUyMGFycm93cyUzRCUyMjElMjIlMjBmb2xkJTNEJTIyMSUyMiUyMHBhZ2UlM0QlMjIxJTIyJTIwcGFnZVNjYWxlJTNEJTIyMSUyMiUyMHBhZ2VXaWR0aCUzRCUyMjgyNyUyMiUyMHBhZ2VIZWlnaHQlM0QlMjIxMTY5JTIyJTIwYmFja2dyb3VuZCUzRCUyMm5vbmUlMjIlMjBtYXRoJTNEJTIyMCUyMiUyMHNoYWRvdyUzRCUyMjAlMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlM0Nyb290JTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0wJTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0xJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMCUyMiUyMCUyRiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214Q2VsbCUyMGlkJTNEJTIyS2g2VVdDcUxFb3V5cUZPSzdudE0tOSUyMiUyMHZhbHVlJTNEJTIyJTIyJTIwc3R5bGUlM0QlMjJlbmRBcnJvdyUzRGNsYXNzaWMlM0JodG1sJTNEMSUzQnJvdW5kZWQlM0QwJTNCZXhpdFglM0QxJTNCZXhpdFklM0QwLjUlM0JleGl0RHglM0QwJTNCZXhpdER5JTNEMCUzQmVudHJ5WCUzRDAlM0JlbnRyeVklM0QwLjUlM0JlbnRyeUR4JTNEMCUzQmVudHJ5RHklM0QwJTNCJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUyMHNvdXJjZSUzRCUyMktoNlVXQ3FMRW91eXFGT0s3bnRNLTI1JTIyJTIwdGFyZ2V0JTNEJTIyRjYyX0J4bjByeDdnZzNWUllyNWgtMCUyMiUyMGVkZ2UlM0QlMjIxJTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhHZW9tZXRyeSUyMHdpZHRoJTNEJTIyNTAlMjIlMjBoZWlnaHQlM0QlMjI1MCUyMiUyMHJlbGF0aXZlJTNEJTIyMSUyMiUyMGFzJTNEJTIyZ2VvbWV0cnklMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteFBvaW50JTIweCUzRCUyMjQ4MS40MzAwMDAwMDAwMDAwNiUyMiUyMHklM0QlMjItNjAlMjIlMjBhcyUzRCUyMnNvdXJjZVBvaW50JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhQb2ludCUyMHglM0QlMjIzMDYlMjIlMjB5JTNEJTIyLTE2MCUyMiUyMGFzJTNEJTIydGFyZ2V0UG9pbnQlMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0MlMkZteEdlb21ldHJ5JTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJLaDZVV0NxTEVvdXlxRk9LN250TS0yNSUyMiUyMHZhbHVlJTNEJTIyU3RlcCUyMDElMjZsdCUzQmJyJTI2Z3QlM0IlMjZsdCUzQmklMjZndCUzQk1peGluZyUyNmx0JTNCJTJGaSUyNmd0JTNCJTIyJTIwc3R5bGUlM0QlMjJyb3VuZGVkJTNEMSUzQndoaXRlU3BhY2UlM0R3cmFwJTNCaHRtbCUzRDElM0Jmb250U2l6ZSUzRDEyJTNCZ2xhc3MlM0QwJTNCc3Ryb2tlV2lkdGglM0QxJTNCc2hhZG93JTNEMCUzQmZpbGxDb2xvciUzRCUyM2Y4Y2VjYyUzQnN0cm9rZUNvbG9yJTNEJTIzYjg1NDUwJTNCJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUyMHZlcnRleCUzRCUyMjElMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteEdlb21ldHJ5JTIweCUzRCUyMjEyMCUyMiUyMHklM0QlMjItMjMwJTIyJTIwd2lkdGglM0QlMjIxMjAlMjIlMjBoZWlnaHQlM0QlMjI0MCUyMiUyMGFzJTNEJTIyZ2VvbWV0cnklMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0MlMkZteENlbGwlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteENlbGwlMjBpZCUzRCUyMkY2Ml9CeG4wcng3Z2czVlJZcjVoLTAlMjIlMjB2YWx1ZSUzRCUyMlN0ZXAlMjAyJTI2bHQlM0JiciUyNmd0JTNCJTI2bHQlM0JpJTI2Z3QlM0JEcnlpbmclMjZsdCUzQiUyRmklMjZndCUzQiUyMiUyMHN0eWxlJTNEJTIycm91bmRlZCUzRDElM0J3aGl0ZVNwYWNlJTNEd3JhcCUzQmh0bWwlM0QxJTNCZm9udFNpemUlM0QxMiUzQmdsYXNzJTNEMCUzQnN0cm9rZVdpZHRoJTNEMSUzQnNoYWRvdyUzRDAlM0JmaWxsQ29sb3IlM0QlMjNmOGNlY2MlM0JzdHJva2VDb2xvciUzRCUyM2I4NTQ1MCUzQiUyMiUyMHZlcnRleCUzRCUyMjElMjIlMjBwYXJlbnQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0xJTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhHZW9tZXRyeSUyMHglM0QlMjIyODAlMjIlMjB5JTNEJTIyLTIzMCUyMiUyMHdpZHRoJTNEJTIyMTIwJTIyJTIwaGVpZ2h0JTNEJTIyNDAlMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC0zJTIyJTIwdmFsdWUlM0QlMjJTdGVwJTIwMyUyNmx0JTNCYnIlMjZndCUzQiUyNmx0JTNCaSUyNmd0JTNCUGFydGljbGUlMjBTaXplJTIwUmVkdWN0aW9uJTI2bHQlM0IlMkZpJTI2Z3QlM0IlMjIlMjBzdHlsZSUzRCUyMnJvdW5kZWQlM0QxJTNCd2hpdGVTcGFjZSUzRHdyYXAlM0JodG1sJTNEMSUzQmZvbnRTaXplJTNEMTIlM0JnbGFzcyUzRDAlM0JzdHJva2VXaWR0aCUzRDElM0JzaGFkb3clM0QwJTNCZmlsbENvbG9yJTNEJTIzZjhjZWNjJTNCc3Ryb2tlQ29sb3IlM0QlMjNiODU0NTAlM0IlMjIlMjB2ZXJ0ZXglM0QlMjIxJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214R2VvbWV0cnklMjB4JTNEJTIyNDQwJTIyJTIweSUzRCUyMi0yMzAlMjIlMjB3aWR0aCUzRCUyMjE5NC41JTIyJTIwaGVpZ2h0JTNEJTIyNDAlMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC01JTIyJTIwdmFsdWUlM0QlMjIlMjIlMjBzdHlsZSUzRCUyMmVuZEFycm93JTNEY2xhc3NpYyUzQmh0bWwlM0QxJTNCcm91bmRlZCUzRDAlM0JleGl0WCUzRDElM0JleGl0WSUzRDAuNSUzQmV4aXREeCUzRDAlM0JleGl0RHklM0QwJTNCZW50cnlYJTNEMCUzQmVudHJ5WSUzRDAuNSUzQmVudHJ5RHglM0QwJTNCZW50cnlEeSUzRDAlM0IlMjIlMjBlZGdlJTNEJTIyMSUyMiUyMHBhcmVudCUzRCUyMldJeVdsTGs2R0pRc3FhVUJLVE5WLTElMjIlMjBzb3VyY2UlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC0wJTIyJTIwdGFyZ2V0JTNEJTIyRjYyX0J4bjByeDdnZzNWUllyNWgtMyUyMiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214R2VvbWV0cnklMjB3aWR0aCUzRCUyMjUwJTIyJTIwaGVpZ2h0JTNEJTIyNTAlMjIlMjByZWxhdGl2ZSUzRCUyMjElMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhQb2ludCUyMHglM0QlMjIzMTYlMjIlMjB5JTNEJTIyLTE5MCUyMiUyMGFzJTNEJTIyc291cmNlUG9pbnQlMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteFBvaW50JTIweCUzRCUyMjMwNiUyMiUyMHklM0QlMjItODAlMjIlMjBhcyUzRCUyMnRhcmdldFBvaW50JTIy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&quot;/>
                    </attachment>
                </content>" id="DocumentReference-documentreference-drug-pq-process-flow-diagram">Document</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/documentreference.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/documentreference.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/documentreference.html#tt-uml">R6</a>]</span><div class="debugOff">id: documentreference-drug-pq-process-flow-diagram</div>
<div class="debugOff"> fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41feb</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DocumentReference-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DocumentReference-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DocumentReference-drug-pq</span></div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <identifier>
                    <system value=&quot;http://example.org/fhir/identifier/document&quot;/>
                    <value value=&quot;FLOW-001&quot;/>">Identifier: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <identifier>
                    <system value=&quot;http://example.org/fhir/identifier/document&quot;/>
                    <value value=&quot;FLOW-001&quot;/>">FLOW-001<span class="greyOff"> (http://example.org/fhir/identifier/document)</span></span></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>">Status: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>"><span>current</span></span></div>
</div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/diagram-type&quot;/>
                        <code value=&quot;ProcessFlowDiagram&quot;/>
                        <display value=&quot;Process Flow Diagram&quot;/>
                    </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/diagram-type&quot;/>
                        <code value=&quot;ProcessFlowDiagram&quot;/>
                        <display value=&quot;Process Flow Diagram&quot;/>">Process Flow Diagram<span class="greyOff"> [ProcessFlowDiagram]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/diagram-type)</span></span></div>
<div class="summaryHiddenOff">
				Content
				<div class="indent org2">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <contentType value=&quot;image/x-png&quot;>">Content Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <contentType value=&quot;image/x-png&quot;>">image/x-png</span></div>
<div><img src="data:image/x-png;base64, iVBORw0KGgoAAAANSUhEUgAAAgQAAAApCAYAAABKrzFXAAAAAXNSR0IArs4c6QAAEjl0RVh0bXhmaWxlACUzQ214ZmlsZSUyMGhvc3QlM0QlMjJFbGVjdHJvbiUyMiUyMG1vZGlmaWVkJTNEJTIyMjAyMy0wNy0wNlQxMyUzQTA4JTNBMDguNDgzWiUyMiUyMGFnZW50JTNEJTIyTW96aWxsYSUyRjUuMCUyMChXaW5kb3dzJTIwTlQlMjAxMC4wJTNCJTIwV2luNjQlM0IlMjB4NjQpJTIwQXBwbGVXZWJLaXQlMkY1MzcuMzYlMjAoS0hUTUwlMkMlMjBsaWtlJTIwR2Vja28pJTIwZHJhdy5pbyUyRjIxLjYuMSUyMENocm9tZSUyRjExMi4wLjU2MTUuMjA0JTIwRWxlY3Ryb24lMkYyNC42LjElMjBTYWZhcmklMkY1MzcuMzYlMjIlMjBldGFnJTNEJTIyNkMxTlFraVpHaXdVNTVadFBEMUQlMjIlMjB2ZXJzaW9uJTNEJTIyMjEuNi4xJTIyJTIwdHlwZSUzRCUyMmRldmljZSUyMiUzRSUwQSUyMCUyMCUzQ2RpYWdyYW0lMjBpZCUzRCUyMkM1UkJzNDNvRGEtS2R6WmVOdHV5JTIyJTIwbmFtZSUzRCUyMlBhZ2UtMSUyMiUzRSUwQSUyMCUyMCUyMCUyMCUzQ214R3JhcGhNb2RlbCUyMGR4JTNEJTIyMTAzNiUyMiUyMGR5JTNEJTIyMTc4MyUyMiUyMGdyaWQlM0QlMjIxJTIyJTIwZ3JpZFNpemUlM0QlMjIxMCUyMiUyMGd1aWRlcyUzRCUyMjElMjIlMjB0b29sdGlwcyUzRCUyMjElMjIlMjBjb25uZWN0JTNEJTIyMSUyMiUyMGFycm93cyUzRCUyMjElMjIlMjBmb2xkJTNEJTIyMSUyMiUyMHBhZ2UlM0QlMjIxJTIyJTIwcGFnZVNjYWxlJTNEJTIyMSUyMiUyMHBhZ2VXaWR0aCUzRCUyMjgyNyUyMiUyMHBhZ2VIZWlnaHQlM0QlMjIxMTY5JTIyJTIwYmFja2dyb3VuZCUzRCUyMm5vbmUlMjIlMjBtYXRoJTNEJTIyMCUyMiUyMHNoYWRvdyUzRCUyMjAlMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlM0Nyb290JTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0wJTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0xJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMCUyMiUyMCUyRiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214Q2VsbCUyMGlkJTNEJTIyS2g2VVdDcUxFb3V5cUZPSzdudE0tOSUyMiUyMHZhbHVlJTNEJTIyJTIyJTIwc3R5bGUlM0QlMjJlbmRBcnJvdyUzRGNsYXNzaWMlM0JodG1sJTNEMSUzQnJvdW5kZWQlM0QwJTNCZXhpdFglM0QxJTNCZXhpdFklM0QwLjUlM0JleGl0RHglM0QwJTNCZXhpdER5JTNEMCUzQmVudHJ5WCUzRDAlM0JlbnRyeVklM0QwLjUlM0JlbnRyeUR4JTNEMCUzQmVudHJ5RHklM0QwJTNCJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUyMHNvdXJjZSUzRCUyMktoNlVXQ3FMRW91eXFGT0s3bnRNLTI1JTIyJTIwdGFyZ2V0JTNEJTIyRjYyX0J4bjByeDdnZzNWUllyNWgtMCUyMiUyMGVkZ2UlM0QlMjIxJTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhHZW9tZXRyeSUyMHdpZHRoJTNEJTIyNTAlMjIlMjBoZWlnaHQlM0QlMjI1MCUyMiUyMHJlbGF0aXZlJTNEJTIyMSUyMiUyMGFzJTNEJTIyZ2VvbWV0cnklMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteFBvaW50JTIweCUzRCUyMjQ4MS40MzAwMDAwMDAwMDAwNiUyMiUyMHklM0QlMjItNjAlMjIlMjBhcyUzRCUyMnNvdXJjZVBvaW50JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhQb2ludCUyMHglM0QlMjIzMDYlMjIlMjB5JTNEJTIyLTE2MCUyMiUyMGFzJTNEJTIydGFyZ2V0UG9pbnQlMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0MlMkZteEdlb21ldHJ5JTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJLaDZVV0NxTEVvdXlxRk9LN250TS0yNSUyMiUyMHZhbHVlJTNEJTIyU3RlcCUyMDElMjZsdCUzQmJyJTI2Z3QlM0IlMjZsdCUzQmklMjZndCUzQk1peGluZyUyNmx0JTNCJTJGaSUyNmd0JTNCJTIyJTIwc3R5bGUlM0QlMjJyb3VuZGVkJTNEMSUzQndoaXRlU3BhY2UlM0R3cmFwJTNCaHRtbCUzRDElM0Jmb250U2l6ZSUzRDEyJTNCZ2xhc3MlM0QwJTNCc3Ryb2tlV2lkdGglM0QxJTNCc2hhZG93JTNEMCUzQmZpbGxDb2xvciUzRCUyM2Y4Y2VjYyUzQnN0cm9rZUNvbG9yJTNEJTIzYjg1NDUwJTNCJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUyMHZlcnRleCUzRCUyMjElMjIlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteEdlb21ldHJ5JTIweCUzRCUyMjEyMCUyMiUyMHklM0QlMjItMjMwJTIyJTIwd2lkdGglM0QlMjIxMjAlMjIlMjBoZWlnaHQlM0QlMjI0MCUyMiUyMGFzJTNEJTIyZ2VvbWV0cnklMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0MlMkZteENlbGwlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteENlbGwlMjBpZCUzRCUyMkY2Ml9CeG4wcng3Z2czVlJZcjVoLTAlMjIlMjB2YWx1ZSUzRCUyMlN0ZXAlMjAyJTI2bHQlM0JiciUyNmd0JTNCJTI2bHQlM0JpJTI2Z3QlM0JEcnlpbmclMjZsdCUzQiUyRmklMjZndCUzQiUyMiUyMHN0eWxlJTNEJTIycm91bmRlZCUzRDElM0J3aGl0ZVNwYWNlJTNEd3JhcCUzQmh0bWwlM0QxJTNCZm9udFNpemUlM0QxMiUzQmdsYXNzJTNEMCUzQnN0cm9rZVdpZHRoJTNEMSUzQnNoYWRvdyUzRDAlM0JmaWxsQ29sb3IlM0QlMjNmOGNlY2MlM0JzdHJva2VDb2xvciUzRCUyM2I4NTQ1MCUzQiUyMiUyMHZlcnRleCUzRCUyMjElMjIlMjBwYXJlbnQlM0QlMjJXSXlXbExrNkdKUXNxYVVCS1ROVi0xJTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhHZW9tZXRyeSUyMHglM0QlMjIyODAlMjIlMjB5JTNEJTIyLTIzMCUyMiUyMHdpZHRoJTNEJTIyMTIwJTIyJTIwaGVpZ2h0JTNEJTIyNDAlMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC0zJTIyJTIwdmFsdWUlM0QlMjJTdGVwJTIwMyUyNmx0JTNCYnIlMjZndCUzQiUyNmx0JTNCaSUyNmd0JTNCUGFydGljbGUlMjBTaXplJTIwUmVkdWN0aW9uJTI2bHQlM0IlMkZpJTI2Z3QlM0IlMjIlMjBzdHlsZSUzRCUyMnJvdW5kZWQlM0QxJTNCd2hpdGVTcGFjZSUzRHdyYXAlM0JodG1sJTNEMSUzQmZvbnRTaXplJTNEMTIlM0JnbGFzcyUzRDAlM0JzdHJva2VXaWR0aCUzRDElM0JzaGFkb3clM0QwJTNCZmlsbENvbG9yJTNEJTIzZjhjZWNjJTNCc3Ryb2tlQ29sb3IlM0QlMjNiODU0NTAlM0IlMjIlMjB2ZXJ0ZXglM0QlMjIxJTIyJTIwcGFyZW50JTNEJTIyV0l5V2xMazZHSlFzcWFVQktUTlYtMSUyMiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214R2VvbWV0cnklMjB4JTNEJTIyNDQwJTIyJTIweSUzRCUyMi0yMzAlMjIlMjB3aWR0aCUzRCUyMjE5NC41JTIyJTIwaGVpZ2h0JTNEJTIyNDAlMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTIwJTJGJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDJTJGbXhDZWxsJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhDZWxsJTIwaWQlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC01JTIyJTIwdmFsdWUlM0QlMjIlMjIlMjBzdHlsZSUzRCUyMmVuZEFycm93JTNEY2xhc3NpYyUzQmh0bWwlM0QxJTNCcm91bmRlZCUzRDAlM0JleGl0WCUzRDElM0JleGl0WSUzRDAuNSUzQmV4aXREeCUzRDAlM0JleGl0RHklM0QwJTNCZW50cnlYJTNEMCUzQmVudHJ5WSUzRDAuNSUzQmVudHJ5RHglM0QwJTNCZW50cnlEeSUzRDAlM0IlMjIlMjBlZGdlJTNEJTIyMSUyMiUyMHBhcmVudCUzRCUyMldJeVdsTGs2R0pRc3FhVUJLVE5WLTElMjIlMjBzb3VyY2UlM0QlMjJGNjJfQnhuMHJ4N2dnM1ZSWXI1aC0wJTIyJTIwdGFyZ2V0JTNEJTIyRjYyX0J4bjByeDdnZzNWUllyNWgtMyUyMiUzRSUwQSUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUyMCUzQ214R2VvbWV0cnklMjB3aWR0aCUzRCUyMjUwJTIyJTIwaGVpZ2h0JTNEJTIyNTAlMjIlMjByZWxhdGl2ZSUzRCUyMjElMjIlMjBhcyUzRCUyMmdlb21ldHJ5JTIyJTNFJTBBJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTIwJTNDbXhQb2ludCUyMHglM0QlMjIzMTYlMjIlMjB5JTNEJTIyLTE5MCUyMiUyMGFzJTNEJTIyc291cmNlUG9pbnQlMjIlMjAlMkYlM0UlMEElMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlMjAlM0NteFBvaW50JTIweCUzRCUyMjMwNiUyMiUyMHklM0QlMjItODAlMjIlMjBhcyUzRCUyMnRhcmdldFBvaW50JTIy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"></div>
</div>
</div>
</div>
<div class="htmlTableRemove"><br style="line-height:6px;"><div class="indent-no-border"><span>Table 1. List of Equipment</span><br><br style="line-height:6px;"><table class="rounded-corners white" id="tabularModeTable" style="width:70%;">
<tr>
<th>Name / Type</th>
<th>Working Capacity (where appropriate)</th>
</tr>
<tr>
<td class="centred">Mixing Vessel</td>
<td class="centred">Capacity: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>">1000 litres</span></td>
</tr>
<tr>
<td class="centred">Receiving Tank</td>
<td class="centred">Capacity: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1200&quot;/>
                        <unit value=&quot;litres&quot;/>">1200 litres</span></td>
</tr>
<tr>
<td class="centred">Blender</td>
<td class="centred">Maximum capacity: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>">1000 litres</span></td>
</tr>
<tr>
<td class="centred">Heated dryer</td>
<td class="centred">Power: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;3&quot;/>
                        <unit value=&quot;kW&quot;/>">3 kW</span></td>
</tr>
<tr>
<td class="centred">Rotating Impeller with 1.5mm screen</td>
<td class="centred">Maximum Speed: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;5000&quot;/>
                        <unit value=&quot;RPM&quot;/>">5000 RPM</span></td>
</tr>
</table>
</div><br style="line-height:6px;"></div>
<div class="htmlTableRemove"><br style="line-height:6px;"><div class="indent-no-border"><span>Table 2. In-Process and Quality Controls</span><br><br style="line-height:6px;"><table class="rounded-corners white" id="tabularModeTable" style="width:70%;">
<tr>
<th>Process Step (name)</th>
<th>Parameter</th>
<th>Acceptance Criteria</th>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">1</span></div>
</td>
<td class="centred"> Parameter - Capacity</td>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>"></span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>">750 litres</span></div>
</td>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">1</span></div>
</td>
<td class="centred"> Parameter - Temperature</td>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>"></span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>">150 °C</span><span class="greyOff"> [Cel] (http://unitsofmeasure.org)</span></div>
</td>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">1</span></div>
</td>
<td class="centred">Controls - pH</td>
<td class="centred">pH must be in range 6.9 to 7.1</td>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>">2</span></div>
</td>
<td class="centred"> Parameter - Maximum Temperature</td>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>"></span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>">40 °C</span><span class="greyOff"> [Cel] (http://unitsofmeasure.org)</span></div>
</td>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>">2</span></div>
</td>
<td class="centred">Controls - Water Content</td>
<td class="centred">Under 2%</td>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>">3</span></div>
</td>
<td class="centred"> Parameter - Rotational Speed</td>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>"></span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>">2500 rpm</span></div>
</td>
</tr>
<tr>
<td class="centred">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>">Step: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>">3</span></div>
</td>
<td class="centred">Controls - Particle Size</td>
<td class="centred">Under 200 microns</td>
</tr>
</table>
</div><br style="line-height:6px;"></div>
<div class="indent summaryUnit planl2"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;1&quot;/>
                    <description value=&quot;Mixing of ingredients&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>
                        </coding>
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-pH&quot;/>
                    <!--goalId value=&quot;goal-control-temp&quot;/-->
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/mixer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/startingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/processingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;processing material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <!--action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlPH&quot;/>
                        </action>
                        <action>
                            <code>
                                <text value=&quot;Control&quot;/>
                            </code>
                            <definitionCanonical value=&quot;ObservationDefinition/ControlTemperature&quot;/>
                        </action-->"><a id="urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265a"><span>Action</span></a><span class="summaryShowsOff"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>"> - 1</span> - <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>">Mixing of ingredients<span class="greyOff"> [Mixing of ingredients]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step)</span></span></span></span><div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">Step (prefix): </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;1&quot;>">1</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>
                        </coding>">Code: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;Mixing of ingredients&quot;/>
                            <display value=&quot;Mixing of ingredients&quot;/>">Mixing of ingredients<span class="greyOff"> [Mixing of ingredients]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step)</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <description value=&quot;Mixing of ingredients&quot;>">Description: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <description value=&quot;Mixing of ingredients&quot;>">Mixing of ingredients</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>">Scale: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>">Production Scale<span class="greyOff"> [PROD]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step-scale)</span></span></span></div>
<div class="summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <goalId value=&quot;goal-control-pH&quot;>">
<div class="summaryHiddenOff">
<div class="indent planl2"><a id="goal-goal-control-pH"><span title="id: goal-control-pH
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <goal id=&quot;goal-control-pH&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - pH&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>
                            </coding>
                            <text value=&quot;pH must be in range 6.9 to 7.1&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </low>
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </high>
                        </detailRange>
                    </target>">Goal</span><span> (goal-control-pH</span>)</a><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    ...
                    <description>
                        <text value=&quot;Controls - pH&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->">Description: </span><span style="white-space:normal;">Controls - pH</span></div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>">Category: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>">Physical Property<span class="greyOff"> [C123456]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category)</span></span></div>
</div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    ...
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>">Priority: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>">Critical<span class="greyOff"> [critical]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example)</span></span></div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    ...
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>
                            </coding>
                            <text value=&quot;pH must be in range 6.9 to 7.1&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </low>
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </high>
                        </detailRange>">Target</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>
                            </coding>
                            <text value=&quot;pH must be in range 6.9 to 7.1&quot;/>">Measure: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;pH&quot;/>
                                <display value=&quot;pH&quot;/>">pH<span class="greyOff"> [pH]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example)</span></span><span style="white-space:normal;"> - Text: pH must be in range 6.9 to 7.1</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <target>
                        ...
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </low>
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>
                            </high>">Detail: </span>from <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <target>
                        <detailRange>
                            <low>
                                <value value=&quot;6.9&quot;/>
                                <unit value=&quot;pH&quot;/>">6.9 pH</span> to <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-pH&quot;>
                    <target>
                        <detailRange>
                            ...
                            <high>
                                <value value=&quot;7.1&quot;/>
                                <unit value=&quot;pH&quot;/>">7.1 pH</span></div>
</div>
</div>
</div>
</div>
<div class="indent planl3 summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>
                            </valueQuantity>
                        </extension>">
					Parameters
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>">Parameter: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>
                                </coding>
                            </valueCodeableConcept>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;Capacity&quot;/>
                                    <display value=&quot;Capacity&quot;/>">Capacity<span class="greyOff"> [Capacity]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/process-parameter)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>">Value Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;750&quot;/>
                                <unit value=&quot;litres&quot;/>">750 litres</span></div>
</div>
<div class="indent planl3 summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>">
					Parameters
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>">Parameter: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>
                                </coding>
                            </valueCodeableConcept>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP&quot;/>
                                    <display value=&quot;Temperature&quot;/>">Temperature<span class="greyOff"> [TEMP]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/process-parameter)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>">Value Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;150&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>">150 °C</span><span class="greyOff"> [Cel] (http://unitsofmeasure.org)</span></div>
</div>
<div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>">Documentation</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <documentation>
                        <type value=&quot;specification-of&quot;>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <documentation>
                        <type value=&quot;specification-of&quot;>"><span>specification-of</span></span></div>
<div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DocumentReference (id: DocumentReference-image)(fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee)

<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <id value=&quot;DocumentReference-image&quot;/>
                <status value=&quot;current&quot;/>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;/>
                    </attachment>
                </content>" id="DocumentReference-DocumentReference-image">Document</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/documentreference.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/documentreference.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/documentreference.html#tt-uml">R6</a>]</span><div class="debugOff">id: DocumentReference-image</div>
<div class="debugOff"> fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee</div>
<div class="summaryHiddenOff">
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>">Status: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>"><span>current</span></span></div>
</div>
<div class="summaryHiddenOff">
				Content
				<div class="indent org2">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;>">url: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;>"><a href="https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png">https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png</a></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/mixer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Blender&quot;/>
                                <display value=&quot;Blender&quot;/>">Blender<span class="greyOff"> [Blender]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class)</span></span></span></div>
<div class="indent devd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/typeReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DeviceDefinition (id: mixer)(fullUrl: urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bad9494d)

<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <id value=&quot;mixer&quot;/>
                <deviceName>
                    <name value=&quot;Blender&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum capacity&quot;/>
                            <display value=&quot;Maximum capacity&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>
                </property>" id="DeviceDefinition-mixer">Device</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/devicedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/devicedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/devicedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: mixer</div>
<div class="debugOff"> fullUrl: urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bad9494d</div>
<div class="summaryHiddenOff"></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <deviceName>
                    <name value=&quot;Blender&quot;/>
                    <type value=&quot;registered-name&quot;/>">Name: </span><span>Blender</span><span> (name type: registered-name)</span></div>
<div class="summaryHiddenOff">
<div class="summaryHiddenOff">
<div class="indent devdl2"><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum capacity&quot;/>
                            <display value=&quot;Maximum capacity&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>
                    </valueQuantity>">Property</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum capacity&quot;/>
                            <display value=&quot;Maximum capacity&quot;/>
                        </coding>">Type: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum capacity&quot;/>
                            <display value=&quot;Maximum capacity&quot;/>">Maximum capacity<span class="greyOff"> [Maximum capacity]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/device-property)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>">Value: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;1000&quot;/>
                        <unit value=&quot;litres&quot;/>">1000 litres</span></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/startingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>">Starting Material<span class="greyOff"> [StartingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;starting material&quot;>">Display: starting material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: startingMaterial)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821153)

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;startingMaterial&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Stelbatosubstance&quot;/>
                </name>" id="SubstanceDefinition-startingMaterial">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatosubstance</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: startingMaterial</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821153</div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatosubstance&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatosubstance&quot;>"><span>Stelbatosubstance</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails2"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                ...
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>">Manufacturer</span><div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: Stelbatolol fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: startingMaterial fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821153)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="Organization (id: substance-manufacturer)(fullUrl: urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d)

<Bundle>
    <entry>
        <resource>
            <Organization>
                <id value=&quot;substance-manufacturer&quot;/>
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>
                </identifier>
                <active value=&quot;true&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>
                </type>
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;/>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>
                    </address>
                </contact>" id="Organization-substance-manufacturer">Organization</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/organization.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/organization.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/organization.html#tt-uml">R6</a>]</span><div class="debugOff">id: substance-manufacturer</div>
<div class="debugOff"> fullUrl: urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d</div><span class="summaryShowsOff"> - AAA Molybdenum Products, Inc.</span><div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>">Identifier: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>">3003040516<span class="greyOff"> (urn:oid:2.16.840.1.113883.4.82)</span></span></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>">Active: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>"><span>true</span></span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;>">Name: </span><span>AAA Molybdenum Products, Inc.</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>">Drug Substance Manufacture<span class="greyOff"> [drug-substance-manufacture]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type)</span></span></div>
<div class="indent org2">
					Contact
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>">Address: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;>">7233 W 116th Pl</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <line value=&quot;Ste C&quot;>">Ste C</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <city value=&quot;Broomfield&quot;>">Broomfield</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <state value=&quot;Colorado&quot;>">Colorado</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <postalCode value=&quot;80020&quot;>">80020</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <country value=&quot;USA&quot;>">USA</span></div>
</div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/processingMaterial&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;processing material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ProcessingMaterial&quot;/>
                                <display value=&quot;Processing Material&quot;/>">Processing Material<span class="greyOff"> [ProcessingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;processing material&quot;>">Display: processing material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: processingMaterial)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821155)

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;processingMaterial&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/manufacturerProcessingMaterial&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Processohol&quot;/>
                </name>" id="SubstanceDefinition-processingMaterial">Substance</span></a><span class="summaryShowsOff"><b> - Processohol</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: processingMaterial</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821155</div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Processohol&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Processohol&quot;>"><span>Processohol</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails2"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                ...
                <manufacturer>
                    <reference value=&quot;Organization/manufacturerProcessingMaterial&quot;/>">Manufacturer</span><div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: processingMaterial fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821155)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="Organization (id: manufacturerProcessingMaterial)(fullUrl: urn:uuid:8d61736c-a6e3-8301-659f-17da402e012a)

<Bundle>
    <entry>
        <resource>
            <Organization>
                <id value=&quot;manufacturerProcessingMaterial&quot;/>
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3010027650&quot;/>
                </identifier>
                <active value=&quot;true&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-product-manufacture&quot;/>
                        <display value=&quot;Drug Product Manufacture&quot;/>
                    </coding>
                </type>
                <name value=&quot;AAA Pharmaceutical, Inc.&quot;/>
                <contact>
                    <address>
                        <line value=&quot;681 Main Street&quot;/>
                        <city value=&quot;Lumberton&quot;/>
                        <state value=&quot;New Jersey&quot;/>
                        <postalCode value=&quot;08048&quot;/>
                        <country value=&quot;USA&quot;/>
                    </address>
                </contact>" id="Organization-manufacturerProcessingMaterial">Organization</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/organization.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/organization.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/organization.html#tt-uml">R6</a>]</span><div class="debugOff">id: manufacturerProcessingMaterial</div>
<div class="debugOff"> fullUrl: urn:uuid:8d61736c-a6e3-8301-659f-17da402e012a</div><span class="summaryShowsOff"> - AAA Pharmaceutical, Inc.</span><div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3010027650&quot;/>">Identifier: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3010027650&quot;/>">3010027650<span class="greyOff"> (urn:oid:2.16.840.1.113883.4.82)</span></span></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>">Active: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>"><span>true</span></span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <name value=&quot;AAA Pharmaceutical, Inc.&quot;>">Name: </span><span>AAA Pharmaceutical, Inc.</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-product-manufacture&quot;/>
                        <display value=&quot;Drug Product Manufacture&quot;/>
                    </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-product-manufacture&quot;/>
                        <display value=&quot;Drug Product Manufacture&quot;/>">Drug Product Manufacture<span class="greyOff"> [drug-product-manufacture]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type)</span></span></div>
<div class="indent org2">
					Contact
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;681 Main Street&quot;/>
                        <city value=&quot;Lumberton&quot;/>
                        <state value=&quot;New Jersey&quot;/>
                        <postalCode value=&quot;08048&quot;/>
                        <country value=&quot;USA&quot;/>">Address: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;681 Main Street&quot;>">681 Main Street</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <city value=&quot;Lumberton&quot;>">Lumberton</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <state value=&quot;New Jersey&quot;>">New Jersey</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <postalCode value=&quot;08048&quot;>">08048</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <country value=&quot;USA&quot;>">USA</span></div>
</div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>">Resulting Material<span class="greyOff"> [ResultingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;resulting material&quot;>">Display: resulting material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: StelbatololAqueousSolution)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821154)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq 

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;StelbatololAqueousSolution&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;/>
                </meta>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;/>
                </name>" id="SubstanceDefinition-StelbatololAqueousSolution">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol Aqueous Solution</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: StelbatololAqueousSolution</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821154</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq</span></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;>"><span>Stelbatolol Aqueous Solution</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
</div>
</div>
</div>
</div>
<div class="indent summaryUnit planl2"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <!-- todo want a range here -->
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;2&quot;/>
                    <description value=&quot;Drying using a heater&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-water-content&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/dryer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>"><a id="urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265a"><span>Action</span></a><span class="summaryShowsOff"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>"> - 2</span> - <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>">Drying<span class="greyOff"> [drying]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step)</span></span></span></span><div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>">Step (prefix): </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;2&quot;>">2</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->">Code: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;drying&quot;/>
                            <display value=&quot;Drying&quot;/>">Drying<span class="greyOff"> [drying]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step)</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <description value=&quot;Drying using a heater&quot;>">Description: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <description value=&quot;Drying using a heater&quot;>">Drying using a heater</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>">Scale: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>">Production Scale<span class="greyOff"> [PROD]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step-scale)</span></span></span></div>
<div class="summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <goalId value=&quot;goal-control-water-content&quot;>">
<div class="summaryHiddenOff">
<div class="indent planl2"><a id="goal-goal-control-water-content"><span title="id: goal-control-water-content
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <goal id=&quot;goal-control-water-content&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Water Content&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>
                            </coding>
                            <text value=&quot;Under 2%&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>
                            </high>
                        </detailRange>
                    </target>">Goal</span><span> (goal-control-water-content</span>)</a><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    ...
                    <description>
                        <text value=&quot;Controls - Water Content&quot;/>
                        <!-- this is mandatory, even though we don't really want it -->">Description: </span><span style="white-space:normal;">Controls - Water Content</span></div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>">Category: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>">Physical Property<span class="greyOff"> [C123456]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category)</span></span></div>
</div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    ...
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>">Priority: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>">Critical<span class="greyOff"> [critical]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example)</span></span></div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    ...
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>
                            </coding>
                            <text value=&quot;Under 2%&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>
                            </high>
                        </detailRange>">Target</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>
                            </coding>
                            <text value=&quot;Under 2%&quot;/>">Measure: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;WaterContent&quot;/>
                                <display value=&quot;Water content&quot;/>">Water content<span class="greyOff"> [WaterContent]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example)</span></span><span style="white-space:normal;"> - Text: Under 2%</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <target>
                        ...
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>
                            </high>">Detail: </span> to <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-water-content&quot;>
                    <target>
                        <detailRange>
                            <high>
                                <value value=&quot;2&quot;/>
                                <unit value=&quot;%&quot;/>">2%</span></div>
</div>
</div>
</div>
</div>
<div class="indent planl3 summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <!-- todo want a range here -->
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>
                            </valueQuantity>
                        </extension>">
					Parameters
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>">Parameter: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>
                                </coding>
                                <text value=&quot;Process temperature must be below 40°C&quot;/>
                            </valueCodeableConcept>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;TEMP-MAX&quot;/>
                                    <display value=&quot;Maximum Temperature&quot;/>">Maximum Temperature<span class="greyOff"> [TEMP-MAX]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/process-parameter)</span></span><span style="white-space:normal;"> - Text: Process temperature must be below 40°C</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>">Value Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;40&quot;/>
                                <unit value=&quot;°C&quot;/>
                                <system value=&quot;http://unitsofmeasure.org&quot;/>
                                <code value=&quot;Cel&quot;/>">40 °C</span><span class="greyOff"> [Cel] (http://unitsofmeasure.org)</span></div>
</div>
<div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>">Documentation</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <documentation>
                        <type value=&quot;specification-of&quot;>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <documentation>
                        <type value=&quot;specification-of&quot;>"><span>specification-of</span></span></div>
<div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DocumentReference (id: DocumentReference-image)(fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee)

<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <id value=&quot;DocumentReference-image&quot;/>
                <status value=&quot;current&quot;/>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;/>
                    </attachment>
                </content>" id="DocumentReference-DocumentReference-image">Document</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/documentreference.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/documentreference.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/documentreference.html#tt-uml">R6</a>]</span><div class="debugOff">id: DocumentReference-image</div>
<div class="debugOff"> fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee</div>
<div class="summaryHiddenOff">
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>">Status: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>"><span>current</span></span></div>
</div>
<div class="summaryHiddenOff">
				Content
				<div class="indent org2">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;>">url: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;>"><a href="https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png">https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png</a></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/dryer&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Dryer&quot;/>
                                <display value=&quot;Dryer&quot;/>">Dryer<span class="greyOff"> [Dryer]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class)</span></span></span></div>
<div class="indent devd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/typeReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DeviceDefinition (id: dryer)(fullUrl: urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bbd9494c)

<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <id value=&quot;dryer&quot;/>
                <deviceName>
                    <name value=&quot;Heated dryer&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Power&quot;/>
                            <display value=&quot;Power&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;3&quot;/>
                        <unit value=&quot;kW&quot;/>
                    </valueQuantity>
                </property>" id="DeviceDefinition-dryer">Device</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/devicedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/devicedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/devicedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: dryer</div>
<div class="debugOff"> fullUrl: urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bbd9494c</div>
<div class="summaryHiddenOff"></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <deviceName>
                    <name value=&quot;Heated dryer&quot;/>
                    <type value=&quot;registered-name&quot;/>">Name: </span><span>Heated dryer</span><span> (name type: registered-name)</span></div>
<div class="summaryHiddenOff">
<div class="summaryHiddenOff">
<div class="indent devdl2"><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Power&quot;/>
                            <display value=&quot;Power&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;3&quot;/>
                        <unit value=&quot;kW&quot;/>
                    </valueQuantity>">Property</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Power&quot;/>
                            <display value=&quot;Power&quot;/>
                        </coding>">Type: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Power&quot;/>
                            <display value=&quot;Power&quot;/>">Power<span class="greyOff"> [Power]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/device-property)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;3&quot;/>
                        <unit value=&quot;kW&quot;/>">Value: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;3&quot;/>
                        <unit value=&quot;kW&quot;/>">3 kW</span></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololAqueousSolution&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>">Starting Material<span class="greyOff"> [StartingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;starting material&quot;>">Display: starting material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: StelbatololAqueousSolution)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821154)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq 

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;StelbatololAqueousSolution&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;/>
                </meta>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;/>
                </name>" id="SubstanceDefinition-StelbatololAqueousSolution">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol Aqueous Solution</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: StelbatololAqueousSolution</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821154</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq</span></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Aqueous Solution&quot;>"><span>Stelbatolol Aqueous Solution</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>">Resulting Material<span class="greyOff"> [ResultingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;resulting material&quot;>">Display: resulting material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: StelbatololGranules)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821113)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq 

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;StelbatololGranules&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;/>
                </meta>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;/>
                </name>" id="SubstanceDefinition-StelbatololGranules">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol Granules</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: StelbatololGranules</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821113</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq</span></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;>"><span>Stelbatolol Granules</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
</div>
</div>
</div>
</div>
<div class="indent summaryUnit planl2"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                    <prefix value=&quot;3&quot;/>
                    <description value=&quot;Particle Size Reduction by using a rotating impeller&quot;/>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->
                    </code>
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>
                    </documentation>
                    <goalId value=&quot;goal-control-particle-size&quot;/>
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/devicedefinition-drug-pq-ex1&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>
                    </participant>
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>
                    </participant>"><a id="urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265a"><span>Action</span></a><span class="summaryShowsOff"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>"> - 3</span> - <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>">Particle Size Reduction<span class="greyOff"> [particleSizeReduction]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step)</span></span></span></span><div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>">Step (prefix): </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <prefix value=&quot;3&quot;>">3</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>
                        </coding>
                        <!--text value=&quot;Step 2 in the process - free text is possible&quot;/-->">Code: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <code>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step&quot;/>
                            <code value=&quot;particleSizeReduction&quot;/>
                            <display value=&quot;Particle Size Reduction&quot;/>">Particle Size Reduction<span class="greyOff"> [particleSizeReduction]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step)</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <description value=&quot;Particle Size Reduction by using a rotating impeller&quot;>">Description: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <description value=&quot;Particle Size Reduction by using a rotating impeller&quot;>">Particle Size Reduction by using a rotating impeller</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>">Scale: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>
                        </valueCoding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-step-scale-pq&quot;>
                        <valueCoding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-step-scale&quot;/>
                            <code value=&quot;PROD&quot;/>
                            <display value=&quot;Production Scale&quot;/>">Production Scale<span class="greyOff"> [PROD]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-step-scale)</span></span></span></div>
<div class="summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <goalId value=&quot;goal-control-particle-size&quot;>">
<div class="summaryHiddenOff">
<div class="indent planl2"><a id="goal-goal-control-particle-size"><span title="id: goal-control-particle-size
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                ...
                <goal id=&quot;goal-control-particle-size&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>
                    </category>
                    <description>
                        <text value=&quot;Controls - Particle Size&quot;/>
                    </description>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>
                    </priority>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>
                            </coding>
                            <text value=&quot;Under 200 microns&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>
                            </high>
                        </detailRange>
                    </target>">Goal</span><span> (goal-control-particle-size</span>)</a><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    ...
                    <description>
                        <text value=&quot;Controls - Particle Size&quot;/>">Description: </span><span style="white-space:normal;">Controls - Particle Size</span></div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>
                        </coding>">Category: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <category>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category&quot;/>
                            <code value=&quot;C123456&quot;/>
                            <display value=&quot;Physical Property&quot;/>">Physical Property<span class="greyOff"> [C123456]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-test-category)</span></span></div>
</div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    ...
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>
                        </coding>">Priority: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <priority>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example&quot;/>
                            <code value=&quot;critical&quot;/>
                            <display value=&quot;Critical&quot;/>">Critical<span class="greyOff"> [critical]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-goalPriority-pq-example)</span></span></div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    ...
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>
                            </coding>
                            <text value=&quot;Under 200 microns&quot;/>
                        </measure>
                        <!--detailString value=&quot;can also be a string&quot;-->
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>
                            </high>
                        </detailRange>">Target</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>
                            </coding>
                            <text value=&quot;Under 200 microns&quot;/>">Measure: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <target>
                        <measure>
                            <coding>
                                <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example&quot;/>
                                <code value=&quot;particle-size&quot;/>
                                <display value=&quot;Particle Size&quot;/>">Particle Size<span class="greyOff"> [particle-size]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-local-codes-drug-pq-example)</span></span><span style="white-space:normal;"> - Text: Under 200 microns</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <target>
                        ...
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>
                            </high>">Detail: </span> to <span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <goal id=&quot;goal-control-particle-size&quot;>
                    <target>
                        <detailRange>
                            <high>
                                <value value=&quot;200&quot;/>
                                <unit value=&quot;microns&quot;/>">200 microns</span></div>
</div>
</div>
</div>
</div>
<div class="indent planl3 summaryHiddenOff" title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>
                        </extension>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>
                            </valueQuantity>
                        </extension>">
					Parameters
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>">Parameter: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>
                                </coding>
                            </valueCodeableConcept>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;parameter&quot;>
                            <valueCodeableConcept>
                                <coding>
                                    <system value=&quot;http://terminology.hl7.org/CodeSystem/process-parameter&quot;/>
                                    <code value=&quot;ROTATIONSPEED&quot;/>
                                    <display value=&quot;Rotational Speed&quot;/>">Rotational Speed<span class="greyOff"> [ROTATIONSPEED]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/process-parameter)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>">Value Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-process-parameters-pq&quot;>
                        <extension url=&quot;value&quot;>
                            <valueQuantity>
                                <value value=&quot;2500&quot;/>
                                <unit value=&quot;rpm&quot;/>">2500 rpm</span></div>
</div>
<div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <documentation>
                        <type value=&quot;specification-of&quot;/>
                        <resourceReference>
                            <reference value=&quot;DocumentReference/DocumentReference-image&quot;/>
                        </resourceReference>">Documentation</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <documentation>
                        <type value=&quot;specification-of&quot;>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <documentation>
                        <type value=&quot;specification-of&quot;>"><span>specification-of</span></span></div>
<div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/resourceReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DocumentReference (id: DocumentReference-image)(fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee)

<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <id value=&quot;DocumentReference-image&quot;/>
                <status value=&quot;current&quot;/>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;/>
                    </attachment>
                </content>" id="DocumentReference-DocumentReference-image">Document</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/documentreference.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/documentreference.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/documentreference.html#tt-uml">R6</a>]</span><div class="debugOff">id: DocumentReference-image</div>
<div class="debugOff"> fullUrl: urn:uuid:74d4c070-6596-8252-8ad9-afa515a41fee</div>
<div class="summaryHiddenOff">
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>">Status: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                ...
                <status value=&quot;current&quot;>"><span>current</span></span></div>
</div>
<div class="summaryHiddenOff">
				Content
				<div class="indent org2">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;>">url: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DocumentReference>
                <content>
                    <attachment>
                        <url value=&quot;https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png&quot;>"><a href="https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png">https://www.accumulus.org/wp-content/uploads/2022/05/Accumulus_Logo_horizontal.png</a></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <!-- this is new in R5 and is not in R4B -->
                            <reference value=&quot;DeviceDefinition/devicedefinition-drug-pq-ex1&quot;/>
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class&quot;/>
                                <code value=&quot;Compression Milling&quot;/>
                                <display value=&quot;Compression Milling&quot;/>">Compression Milling<span class="greyOff"> [Compression Milling]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-manufacturing-equipment-class)</span></span></span></div>
<div class="indent devd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/typeReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="DeviceDefinition (id: devicedefinition-drug-pq-ex1)(fullUrl: urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bad9494c)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DeviceDefinition-drug-pq 

<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <id value=&quot;devicedefinition-drug-pq-ex1&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DeviceDefinition-drug-pq&quot;/>
                </meta>
                <deviceName>
                    <name value=&quot;Rotating Impeller with 1.5mm screen&quot;/>
                    <type value=&quot;registered-name&quot;/>
                </deviceName>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum Speed&quot;/>
                            <display value=&quot;Maximum Speed&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;5000&quot;/>
                        <unit value=&quot;RPM&quot;/>
                    </valueQuantity>
                </property>" id="DeviceDefinition-devicedefinition-drug-pq-ex1">Device</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/devicedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/devicedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/devicedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: devicedefinition-drug-pq-ex1</div>
<div class="debugOff"> fullUrl: urn:uuid:82a39a18-91cf-a19d-76c1-a9e8bad9494c</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DeviceDefinition-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DeviceDefinition-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/DeviceDefinition-drug-pq</span></div>
<div class="summaryHiddenOff"></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <deviceName>
                    <name value=&quot;Rotating Impeller with 1.5mm screen&quot;/>
                    <type value=&quot;registered-name&quot;/>">Name: </span><span>Rotating Impeller with 1.5mm screen</span><span> (name type: registered-name)</span></div>
<div class="summaryHiddenOff">
<div class="summaryHiddenOff">
<div class="indent devdl2"><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                ...
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum Speed&quot;/>
                            <display value=&quot;Maximum Speed&quot;/>
                        </coding>
                    </type>
                    <valueQuantity>
                        <value value=&quot;5000&quot;/>
                        <unit value=&quot;RPM&quot;/>
                    </valueQuantity>">Property</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum Speed&quot;/>
                            <display value=&quot;Maximum Speed&quot;/>
                        </coding>">Type: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    <type>
                        <coding>
                            <system value=&quot;http://terminology.hl7.org/CodeSystem/device-property&quot;/>
                            <code value=&quot;Maximum Speed&quot;/>
                            <display value=&quot;Maximum Speed&quot;/>">Maximum Speed<span class="greyOff"> [Maximum Speed]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/device-property)</span></span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;5000&quot;/>
                        <unit value=&quot;RPM&quot;/>">Value: <span title="
<Bundle>
    <entry>
        <resource>
            <DeviceDefinition>
                <property>
                    ...
                    <valueQuantity>
                        <value value=&quot;5000&quot;/>
                        <unit value=&quot;RPM&quot;/>">5000 RPM</span></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/StelbatololGranules&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;starting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;StartingMaterial&quot;/>
                                <display value=&quot;Starting Material&quot;/>">Starting Material<span class="greyOff"> [StartingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;starting material&quot;>">Display: starting material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: StelbatololGranules)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821113)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq 

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;StelbatololGranules&quot;/>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;/>
                </meta>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;/>
                </name>" id="SubstanceDefinition-StelbatololGranules">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol Granules</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: StelbatololGranules</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821113</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">Profile: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <meta>
                    <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/SubstanceDefinition-component-substance-drug-pq</span></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol Granules&quot;>"><span>Stelbatolol Granules</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
</div>
</div>
<div class="indent planl3"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    ...
                    <participant>
                        <typeReference>
                            <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-manufacturing-participant-pq&quot;>
                                <valueReference>
                                    <reference value=&quot;SubstanceDefinition/Stelbatolol&quot;/>
                                </valueReference>
                            </extension>
                            <display value=&quot;resulting material&quot;/>
                            <!-- added to suppress IG warning about empty reference -->
                        </typeReference>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>
                        </role>">Participant</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        ...
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>
                            </coding>"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <role>
                            <coding>
                                <system value=&quot;http://terminology.hl7.org/CodeSystem/manufacturing-participant-role&quot;/>
                                <code value=&quot;ResultingMaterial&quot;/>
                                <display value=&quot;Resulting Material&quot;/>">Resulting Material<span class="greyOff"> [ResultingMaterial]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/manufacturing-participant-role)</span></span></span></div>
<div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <PlanDefinition>
                <action>
                    <participant>
                        <typeReference>
                            ...
                            <display value=&quot;resulting material&quot;>">Display: resulting material</span></div>
</div>
<div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (PlanDefinition/valueReference, id: manufacturingProcess-unlinked fullUrl: urn:uuid:bf6b038b-1334-3dd4-a552-65c169e2265aurl (canonical): http://example-server.com/fhir/PlanDefinition/bf6b038b-1334-3dd4-a552-65c169e2265a)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (Ingredient/code, id: productIngredient fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d6)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: Stelbatolol)(fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152)

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;Stelbatolol&quot;/>
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>
                </manufacturer>
                <name>
                    <name value=&quot;Stelbatolol&quot;/>
                </name>" id="SubstanceDefinition-Stelbatolol">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: Stelbatolol</div>
<div class="debugOff"> fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152</div>
<div class="summaryHiddenOff">
<div class="indent sbddetails">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol&quot;>">Name: </span><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <name>
                    <name value=&quot;Stelbatolol&quot;>"><span>Stelbatolol</span></span></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff">
<div class="indent sbddetails2"><span title="
<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                ...
                <manufacturer>
                    <reference value=&quot;Organization/substance-manufacturer&quot;/>">Manufacturer</span><div class="indent org summaryUnit">
<div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: Stelbatolol fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821152)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (SubstanceDefinition/manufacturer, id: startingMaterial fullUrl: urn:uuid:c458791f-7cb8-428e-83f7-8a205f821153)<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="Organization (id: substance-manufacturer)(fullUrl: urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d)

<Bundle>
    <entry>
        <resource>
            <Organization>
                <id value=&quot;substance-manufacturer&quot;/>
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>
                </identifier>
                <active value=&quot;true&quot;/>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>
                </type>
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;/>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>
                    </address>
                </contact>" id="Organization-substance-manufacturer">Organization</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/organization.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/organization.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/organization.html#tt-uml">R6</a>]</span><div class="debugOff">id: substance-manufacturer</div>
<div class="debugOff"> fullUrl: urn:uuid:9fe98cfa-9245-8313-0fc5-d15e613b5d6d</div><span class="summaryShowsOff"> - AAA Molybdenum Products, Inc.</span><div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>">Identifier: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <identifier>
                    <!-- FDA establishment identifier -->
                    <system value=&quot;urn:oid:2.16.840.1.113883.4.82&quot;/>
                    <value value=&quot;3003040516&quot;/>">3003040516<span class="greyOff"> (urn:oid:2.16.840.1.113883.4.82)</span></span></div>
<div class="debugOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>">Active: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <active value=&quot;true&quot;>"><span>true</span></span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <name value=&quot;AAA Molybdenum Products, Inc.&quot;>">Name: </span><span>AAA Molybdenum Products, Inc.</span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                ...
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>
                    </coding>">Type: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <type>
                    <coding>
                        <system value=&quot;http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type&quot;/>
                        <code value=&quot;drug-substance-manufacture&quot;/>
                        <display value=&quot;Drug Substance Manufacture&quot;/>">Drug Substance Manufacture<span class="greyOff"> [drug-substance-manufacture]</span><span class="greyOff"> (http://terminology.hl7.org/CodeSystem/pharmaceutical-organization-type)</span></span></div>
<div class="indent org2">
					Contact
					<div><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;/>
                        <line value=&quot;Ste C&quot;/>
                        <city value=&quot;Broomfield&quot;/>
                        <state value=&quot;Colorado&quot;/>
                        <postalCode value=&quot;80020&quot;/>
                        <country value=&quot;USA&quot;/>">Address: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        <line value=&quot;7233 W 116th Pl&quot;>">7233 W 116th Pl</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <line value=&quot;Ste C&quot;>">Ste C</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <city value=&quot;Broomfield&quot;>">Broomfield</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <state value=&quot;Colorado&quot;>">Colorado</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <postalCode value=&quot;80020&quot;>">80020</span>, <span title="
<Bundle>
    <entry>
        <resource>
            <Organization>
                <contact>
                    <address>
                        ...
                        <country value=&quot;USA&quot;>">USA</span></div>
</div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="debugOff"></div>
</div>
</div>
</body>
<style>

@media all {

    /* Rik - consolas works better if text has to align but doesn't look so good.
       text size adjust gives better scaling on mobile devices, and also overrides default behaviour where
       only "full with" text gets scaled (so some divs do, and others dont) 150% looks ok on iPad Safari, but too big on iPad Chrome */
    .divBody { font:10pt 'Verdana'; margin-right:1.5em; margin-top:0.5em; -webkit-text-size-adjust:150%; }

    .indent {
        margin-left:1em; 	/* controls line to line indent */
        text-indent:-1em; 	/* moves text back to right, so that other parts of the div are still at the left */
        margin-right:1em;
        text-indent:0em;
        margin-right:0em;
        margin-top:0.2em;
        margin-bottom:-0.1em;
        padding-bottom:0.1em; /* at bottom of text */
        background-Color:#E6E0E1;
        border:2px solid white;
	    transform:translate(-2px, -2px);
	    border-radius: 5px;
	    visibility:visible; /* this is so that the outer border doesn't hide these */
    }
    .indent-right {
        margin-right:0.7em;
    }
    .indent-no-border {
        margin-left:1em; 	/* controls line to line indent */
        text-indent:-1em; 	/* moves text back to right, so that other parts of the div are still at the left */
        margin-right:1em;
        text-indent:0em;
        margin-right:0em;
        margin-top:0.2em;
        margin-bottom:-0.1em;
        padding-bottom:0.1em; /* at bottom of text */
	    transform:translate(-2px, -2px);
		visibility:visible;
    }
	.bundle { background-Color: #e0dede }
    .bundleBorder {
        border:2px solid #cfcfcf;
	    border-radius: 5px;
	    margin: -1px;
        background-Color: #e0dede;
    }
    .visible { visibility:visible }

    .modifierExtension { font-weight:bold; color:red; }

    .white { background-Color:white }

    .pat { background-Color:#ffe699 }
    .patl2 { background-Color:#fae8b1 }
    .patl3 { background-Color:#fff1c7 }
    .patl4 { background-Color:#fff4d4 }
    
    .body { background-Color:#e3cd8a }
    .bodyl2 { background-Color:#e0cf99 }

    .comp { background-Color:#F5DEB3 }
    .compl2 { background-Color:#f5e4c4 }
    .compl3 { background-Color:#f5e8d0 }
    .compText { background-Color:#f5e8d0 }

    .mpd { background-Color:#ffe699 }
    .mpdl2 { background-Color:#fcebb6 }
    .mpdl3 { background-Color:#fcf0ca }
    .mpdl4 { background-Color:#fff6d9 }
    .mpdl5 { background-Color:#fffaeb }

    .task { background-Color:#fcb568 }
    .task2 { background-Color:#ffd8ad }
    .task3 { background-Color:#ffdfbd }

    .proc { background-Color:#fcb568 }
    .procl2 { background-Color:#ffd8ad }
    .procl3 { background-Color:#ffdfbd }

    .prov { background-Color:#b4b4b4 }

    .cui { background-Color:#d9d2e9 }
    .cuidetails { background-Color:#e6e1f0 }
    .cuidetails2 { background-Color:#ebe9f0 }

    .sbd,.hcs { background-Color:#affad5 }
    .sbddetails,.hcsl2 { background-Color:#c7fce2 }
    .sbddetails2,.hcsl3 { background-Color:#d4fae8 }
    .sbddetails3 { background-Color:#e3fcf0 }

    .apd { background-Color:#d5a6bd; word-wrap:break-all; }
    .apdl2 { background-Color:#e3c5d4; }
    .apdl3 { background-Color:#edd1df; }

    .allergy { background-Color:#d5a6bd; }
    .allergyl2 { background-Color:#d6bcc9; }
    .allergyl3 { background-Color:#d9cad1; }
    .allergyl4 { background-Color:#d9d4d6; }

    .adverseEvent { background-Color:#d6bcc9; }
    .adverseEventl2 { background-Color:#d9cad1; }
    .adverseEventl3 { background-Color:#d9d4d6; }

    .ppd { background-Color:#b6d7a8; width:70%; }
    .ppdl2, .ppdpackage { background-Color:#c2deb6 }
    .ppdl3, .ppdpackageitem { background-Color:#daf0d1 }
    .ppdl4  { background-Color:#e4f2df }

    .obs { background-Color:#b6d7a8; width:75%; }
    .obsl2 { background-Color:#c2deb6 }
    .obsl3 { background-Color:#d4ebca }

    .obsDef { background-Color:#93ad87; width:75%; }
    .obsDefl2 { background-Color:#a8c79b; }
    .obsDefl3 { background-Color:#b6d7a8; }

    .enc { background-Color:#d8f7a3 }
    .encl2 { background-Color: #e1fcb3 }
    .encl3 { background-Color:#e7ffbd }

    .prr { background-Color:#bfbfbf }
    .prrl2 { background-Color:#cfcfcf }
    
    .orgdark { background-Color:#bfbfbf }
    .file { background-Color:#bfbfbf }

    .pra { background-Color:#cfcfcf }
    .org { background-Color:#cfcfcf }
    .act { background-Color:#cfcfcf }
    .plan { background-Color:#cfcfcf }

    .imm { background-Color:#83bdd6 }
    .imml2 { background-Color: #afcedb }
    .imml3 { background-Color: #bde1f0 }

    .org2,.act2,.pral2,.planl2 { background-Color:#dfdfdf }
    .loc { background-Color:#dfdfdf }
    .org3,.act3,.planl3 { background-Color:#ededed }
	.org4,.act4,.planl4 { background-Color:#f2f2f2 }
	.org5 { background-Color:#f7f7f7 }

    .man {  background-Color:#a4c1f4 }
    .manl2 { background-Color:#c2d7fc }
    .manl3 { background-Color:#d9e7ff }
    .manl4 { background-Color:#e8f1ff }
    .manl5 { background-Color:#f5f9ff }

    .med {  background-Color:#a4c1f4 }
    .medl2 { background-Color:#b8cef5 }
    .medl3 { background-Color:#cedcf5 }
    .medl4 { background-Color:#dfe7f7 }

    .ing { background-Color:#f4cccc }
    .ingsub { background-Color:#f7d7d7 }
    .ingsubstr { background-Color:#fce3e3 }
    .ingrefsub { background-Color:#ffeded }

    .subd { background-Color:#b4a7d6 }
    .regauth { background-Color:#82e0dc }
    .regauthl2 { background-Color:#98ebe7 }
    .regauthcase { background-Color:#98ebe7 }
    .regauthcaseapp { background-Color:#aaf2ef }

    .medreq { background-Color:#82e0dc }
    .medreql2 { background-Color:#98ebe7 }

    .medstat { background-Color:#82e0dc }
    .medstatl2 { background-Color:#c2fffc }
    .medstatl3 { background-Color:#d4fffd }
    .medstatl4 { background-Color:#e8fcfc }
    .medstatl5 { background-Color:#f2fcfc }

    .serviceReq { background-Color:#c2fffc }
    .serviceReql2 { background-Color:#d4fffd }
    .serviceReql3 { background-Color:#e8fcfc }
    .serviceReql4 { background-Color:#f2fcfc }

    .supplyDel { background-Color:#5dded8 }
    .supplyDell2 { background-Color:#93ede9 }

	.cond { background-Color:#f4cccc }
    .condl2 { background-Color:#f5dcdc }
    .condl3 { background-Color:#f5e6e6 }

    .devd { background-Color:#b7b7b7 }
    .devdl2 { background-Color:#cfcfcf }
    .devdl3  { background-Color:#e3e3e3 }

    .flag { background-Color:#fffd8f }
    .flagl2 { background-Color:#fffda1 }
    .flagl3 { background-Color:#fcfbb6 }

    .consent { background-Color:#ffb68f }
    .consentl2 { background-Color:#fcc7ac }
    .consentl3 { background-Color: #ffd3bd }
    .consentl4 { background-Color: #ffe0d1 }

	.openButton { width: 12px;
					position: absolute;
        			top: 0px;
       				right: 2px;
       				color:white;
       				visibility:hidden }

 	div:has(div.summaryHidden) > span.openButton { visibility:visible }

	.noUnderline { text-decoration: none; color: inherit; }
	.noUnderline:hover { text-decoration: underline; color: revert; }

    .grey { color:dimgray  }
    .greyOff { color:dimgray; display:none  }
    .debug { color:#990000  }
    .debugOff { display:none }
    .debugBorder { visibility:visible }
    .debugOffBorder { visibility:hidden }

    .summaryHiddenOff { }
    .summaryHidden { display:none }
    .summaryShowsOff { display:none }
    .summaryShows { }

    .remove,.imageRemove,.commentRemove,.provenanceRemove,.taskRemove,.htmlTableRemove { }
    .removeOff,.imageRemoveOff,.commentRemoveOff,.provenanceRemoveOff,.taskRemoveOff,.htmlTableRemoveOff { display:none }

    .resetDebug { visibility:visible; }

	.controls { position: sticky;
				top:8px;
				float:right;
				clear:right;
				width:290px;
				overflow: hidden;
				height:18px;
				border: solid 1px grey;
				border-radius: 5px;
				margin-right: 23px;
				z-index:99;
				background-Color:#ffe699;
				font:10pt 'Verdana';
	}

	.image { position: sticky;
				top:8px;
				float:right;
				clear:right;
				border: solid 1px grey;
				border-radius: 5px;
				padding: 2px;
				z-index:99;
				margin-right: 23px;
				background-color:white;
				font:10pt 'Verdana';
	}

	.comment { position: sticky;
				top:8px;
				width:297.5px;
				border-radius: 5px;
				float:right;
				clear:right;
				border: solid 1px grey;
				z-index:99;
				margin-right: 23px;
				padding-left: 8px;
				background-color:white;
				font:10pt 'Verdana';
	}
	.instanceComment { text-decoration-line: underline;
					   text-decoration-style: dotted;
					   text-decoration-color: red; cursor: help; }

	.narrativeLink { text-decoration-line: underline;
					   text-decoration-style: dotted;
					   text-decoration-color: green; }
					   
    .bold { font-weight:bold; }
    .italic { font-style:italic; }

	.hand { cursor: pointer; }
    .button { text-decoration:underline; cursor: pointer; color:gray; }
    .buttonLabel { color:gray; }
    .buttonNoUnderline { cursor: pointer; color:gray; }
    .buttonNoUnderlineHidden { cursor: pointer; color:#ffe699; }
    .buttonNoUnderlineHidden:hover { color:gray; }

	sup { cursor: default; }
	.rotate-left { transform: rotate(-90deg) }

	.plainLink  { text-decoration: none; color: inherit; }
	.plainLink:visited { text-decoration: none; color: inherit; }

	.greyScale { -moz-filter:grayscale(100%);webkit-filter:grayscale(100%);filter:gray;filter:grayscale(100%) }
	
    .json-key { color:#000096 }
    .json-string { color:#994328 }
    .json-number { color:blue }
    .json-boolean { color:red }
    .json-null { color:green }
	
	th { background-color: #81BEF7; }
	td { padding: 3px; font:10pt 'Verdana'; }
	th { padding: 3px; font:10pt 'Verdana'; } /* seems to need setting explicitly, on site */

	.raised-border-td {
	  position: relative;
	}
	.raised-border-td::before {
	  content: "";
	  position: absolute;
	  top: -1px; /* Raise the border by 1px */
	  left: 0;
	  width: 100%;
	  border-top: 1px solid #000; /* 1px solid black border on the top */
	}
	
	table.rounded-corners {
	 	/* Change these properties */
	 	--border: 1px solid black;
	 	border-radius: 5px;
		font:10pt 'Verdana';
	
	 	/* Don't change these properties */
	 	border-spacing: 0;
	 	border-collapse: separate;
	 	border: var(--border);
	 	overflow: hidden;
	}
	table.white { background-color:white; }
	
	/* Apply a border to the right of all but the last column */
	table.rounded-corners th:not(:last-child),
	table.rounded-corners td:not(:last-child) {
	 border-right: var(--border);
	}
	
	/* Apply a border to the bottom of all but the last row */
	table.rounded-corners>thead>tr:not(:last-child)>th,
	table.rounded-corners>thead>tr:not(:last-child)>td,
	table.rounded-corners>tbody>tr:not(:last-child)>th,
	table.rounded-corners>tbody>tr:not(:last-child)>td,
	table.rounded-corners>tfoot>tr:not(:last-child)>th,
	table.rounded-corners>tfoot>tr:not(:last-child)>td,
	table.rounded-corners>tr:not(:last-child)>td,
	table.rounded-corners>tr:not(:last-child)>th,
	table.rounded-corners>thead:not(:last-child),
	table.rounded-corners>tbody:not(:last-child),
	table.rounded-corners>tfoot:not(:last-child) {
	 border-bottom: var(--border);
	}
	td.centred { text-align:center; }
}
	</style><!--
		Status information:
		First resource in bundle:PlanDefinition
		Single resource bundle:false
		Single resource bundle Not Patient Or Bundle:false
		Single resource Not Patient:false
		Patient document:false
		General Bundle:false
		Not patient related:true
		=>Patient Centric Mode:false
		SubstanceDef Centric Mode:false
		Assumed profile:-->
</html>

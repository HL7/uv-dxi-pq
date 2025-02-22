The HTML rendering below shows a synthetic Quality data example for Common Technical Document (CTD) Module 3: Quality, section 3.2.P.3 Manufacture, subsection 3.2.P.3.2 Batch Formula.
<html>
<body>
<div class="divBody">
<p>
						This is the same data as in the example files here in <a href="Bundle-bundle-batch-formula-pq-ex1.xml.html">xml</a> and in <a href="Bundle-bundle-batch-formula-pq-ex1.json.html">json</a>, presented for easier viewing.
						Hovering on words below will show the corresponding sections of the underlying data.
					</p>
</div>
<div class="greyable">
<div class="divBody">
<div style="position:relative" class="summaryUnit">
<div class="debugOffBorder">
<div class="bundleBorder">
<div class="debugOff">
<div class="bundle"><a class="plainLink"><span class="bold" title="Bundle (id: bundle-batch-formula-pq-ex1)
Profile: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-batch-formula-pq 

<Bundle>
    <id value=&quot;bundle-batch-formula-pq-ex1&quot;/>
    <meta>
        <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-batch-formula-pq&quot;/>
    </meta>
    <type value=&quot;collection&quot;/>
    <!-- MedicinalProductDefinition - the main resource in any product scenario -->
    <entry>
        <fullUrl value=&quot;urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d5&quot;/>
        <resource>
            <!-- Section 1.1 - DP Identification -->
            <MedicinalProductDefinition>
                <id value=&quot;medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                <name>
                    <productName value=&quot;Stalbatolol&quot;/>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>
                    </type>
                </name>
            </MedicinalProductDefinition>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a65&quot;/>
        <resource>
            <Ingredient>
                <id value=&quot;ingredient1&quot;/>
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
                            <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>
            </Ingredient>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:b89fd9d2-80f9-0cfb-70a1-5a6572e73a65&quot;/>
        <resource>
            <Ingredient>
                <id value=&quot;excipient1&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>
            </Ingredient>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:b89ed9d2-81f9-0cfb-70a1-5a6572e73a65&quot;/>
        <resource>
            <Ingredient>
                <id value=&quot;excipient2&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>
            </Ingredient>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a66&quot;/>
        <resource>
            <Ingredient>
                <id value=&quot;excipient3&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>
            </Ingredient>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:b89ed9d2-80f9-0cfb-70b1-5a6572e73a66&quot;/>
        <resource>
            <Ingredient>
                <id value=&quot;excipient4&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>
            </Ingredient>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:4cf2cbba-33e6-1124-9bf2-1c6756380474&quot;/>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;substance1&quot;/>
                <name>
                    <name value=&quot;Stelbatolol&quot;/>
                </name>
            </SubstanceDefinition>
        </resource>
    </entry>
    <!-- Section 7 - Batch Formula -->
    <entry>
        <fullUrl value=&quot;urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070&quot;/>
        <resource>
            <Medication>
                <id value=&quot;medication-batch-formula-unlinked&quot;/>
                <contained>
                    <Substance>
                        <id value=&quot;substanceIngredient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-2&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-3&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-4&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <code>
                    <!-- some other cases link via plandef and activity.product -->
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>
                    </extension>
                    <text value=&quot;Large Batch of Stelbatolol&quot;/>
                </code>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceIngredient-1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;true&quot;/>
                    <strengthQuantity>
                        <value value=&quot;10.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-1&quot;/>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;104.72&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-2&quot;/>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;9.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-3&quot;/>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;2.90&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-4&quot;/>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;1.44&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;722000&quot;/>
                            <unit value=&quot;tablets&quot;/>
                        </valueQuantity>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                </batch>
            </Medication>
        </resource>
    </entry>
    <entry>
        <fullUrl value=&quot;urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071&quot;/>
        <resource>
            <Medication>
                <id value=&quot;medication-batch-formula-2-unlinked&quot;/>
                <contained>
                    <Substance>
                        <id value=&quot;substanceIngredient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-2&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-3&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-4&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <code>
                    <!-- some other cases link via plandef and activity.product -->
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>
                    </extension>
                    <text value=&quot;Small Batch of Stelbatolol&quot;/>
                </code>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceIngredient-1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;true&quot;/>
                    <strengthQuantity>
                        <value value=&quot;5.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-1&quot;/>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;52.36&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-2&quot;/>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;5.99&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-3&quot;/>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;1.45&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-4&quot;/>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;0.72&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;371000&quot;/>
                            <unit value=&quot;tablets&quot;/>
                        </valueQuantity>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                </batch>
            </Medication>
        </resource>
    </entry>" id="Bundle-bundle-batch-formula-pq-ex1">Bundle</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/bundle.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/bundle.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/bundle.html#tt-uml">R6</a>]</span><div class="debugOff">id: bundle-batch-formula-pq-ex1</div>
<div class="debugOff"></div>
<div class="debugOff"><span title="
<Bundle>
    <meta>
        <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-batch-formula-pq&quot;>">Profile: </span><span title="
<Bundle>
    <meta>
        <profile value=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-batch-formula-pq&quot;>">http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Bundle-batch-formula-pq</span></div>
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
<div class="indent mpd summaryUnit"><a class="plainLink"><span class="bold" title="MedicinalProductDefinition (id: medicinalproductdefinition-drug-product-dxpq-ex1)(fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d5)

<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                <id value=&quot;medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                <name>
                    <productName value=&quot;Stalbatolol&quot;/>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>
                    </type>
                </name>" id="MedicinalProductDefinition-medicinalproductdefinition-drug-product-dxpq-ex1">Product</span></a><span class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/medicinalproductdefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/medicinalproductdefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/medicinalproductdefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: medicinalproductdefinition-drug-product-dxpq-ex1</div>
<div class="debugOff"> fullUrl: urn:uuid:a0694a7a-aafa-4cbe-8135-c788a9a4d3d5</div></span><div class="summaryHiddenOff"></div><span class="summaryShowsOff"><b> - </b></span><span title="
<Bundle>
    <entry>
        <resource>
            <MedicinalProductDefinition>
                ...
                <name>
                    <productName value=&quot;Stalbatolol&quot;/>
                    <type>
                        <coding>
                            <system value=&quot;http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example&quot;/>
                            <code value=&quot;Proprietary&quot;/>
                            <display value=&quot;Proprietary&quot;/>
                        </coding>
                    </type>" class="bold"><span class="summaryHiddenOff">Name: </span><span>Stalbatolol</span></span><div class="summaryHiddenOff">
<div><span title="
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
                            <display value=&quot;Proprietary&quot;/>">Proprietary<span class="greyOff"> [Proprietary]</span><span class="greyOff"> (http://hl7.org/fhir/uv/pharm-quality/CodeSystem/cs-productNameType-pq-example)</span></span></div>
</div>
<div class="summaryHiddenOff"></div><br style="line-height:6px;"><div class="htmlTableRemove">
<div class="indent org">
<div class="indent-no-border"><br style="line-height:6px;"><span><b>Batch Formula : </b><b><a href="#Medication-medication-batch-formula-unlinked">Large Batch of Stelbatolol</a></b></span><br style="line-height:6px;"><span>The batch quantities shown represent the full scale manufacturing process for which the batch size is approximately </span><span><a href="#Medication-medication-batch-formula-unlinked" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>">130 kg</a></span><span>, producing approximately </span><span><a href="#Medication-medication-batch-formula-unlinked" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;722000&quot;/>
                            <unit value=&quot;tablets&quot;/>">722000 tablets</a></span><span>.</span><br><br style="line-height:6px;"><table class="rounded-corners white" id="tabularModeTable" style="width:70%;">
<tr>
<th></th>
<th><b>mg/tablet</b></th>
<th><b>Kg/batch</b></th>
</tr>
<tr><td colspan="3"><b>Active Ingredient:</b></td></tr>
<tr>
<td><a href="#Ingredient-ingredient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Stelbatolol&quot;>">Stelbatolol</a></td>
<td><a href="#Ingredient-ingredient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;>">15.2</a></td>
<td><a href="#Medication-medication-batch-formula-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;10.98&quot;>">10.98</a></td>
</tr>
<tr><td colspan="3"><b>Other Ingredients:</b></td></tr>
<tr>
<td><a href="#Ingredient-excipient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Mannitol&quot;>">Mannitol</a></td>
<td><a href="#Ingredient-excipient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;>">145.0</a></td>
<td><a href="#Medication-medication-batch-formula-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;104.72&quot;>">104.72</a></td>
</tr>
<tr>
<td><a href="#Ingredient-excipient2" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Maize starch&quot;>">Maize starch</a></td>
<td><a href="#Ingredient-excipient2" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;>">13.8</a></td>
<td><a href="#Medication-medication-batch-formula-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;9.98&quot;>">9.98</a></td>
</tr>
<tr>
<td><a href="#Ingredient-excipient3" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;>">Calcium carboxymethylcellulose</a></td>
<td><a href="#Ingredient-excipient3" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;>">4.0</a></td>
<td><a href="#Medication-medication-batch-formula-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;2.90&quot;>">2.90</a></td>
</tr>
<tr>
<td><a href="#Ingredient-excipient4" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Magnesium stearate&quot;>">Magnesium stearate</a></td>
<td><a href="#Ingredient-excipient4" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;>">2.0</a></td>
<td><a href="#Medication-medication-batch-formula-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;1.44&quot;>">1.44</a></td>
</tr>
<tr>
<td><b>Total Weight</b></td>
<td><b>180.0</b></td>
<td><b>130.0</b></td>
</tr>
</table><br style="line-height:6px;"><br style="line-height:6px;"><span><b>Batch Formula : </b><b><a href="#Medication-medication-batch-formula-2-unlinked">Small Batch of Stelbatolol</a></b></span><br style="line-height:6px;"><span>The batch quantities shown represent the full scale manufacturing process for which the batch size is approximately </span><span><a href="#Medication-medication-batch-formula-2-unlinked" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>">65 kg</a></span><span>, producing approximately </span><span><a href="#Medication-medication-batch-formula-2-unlinked" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;371000&quot;/>
                            <unit value=&quot;tablets&quot;/>">371000 tablets</a></span><span>.</span><br><br style="line-height:6px;"><table class="rounded-corners white" id="tabularModeTable" style="width:70%;">
<tr>
<th></th>
<th><b>mg/tablet</b></th>
<th><b>Kg/batch</b></th>
</tr>
<tr><td colspan="3"><b>Active Ingredient:</b></td></tr>
<tr>
<td><a href="#Ingredient-ingredient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Stelbatolol&quot;>">Stelbatolol</a></td>
<td><a href="#Ingredient-ingredient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;>">15.2</a></td>
<td><a href="#Medication-medication-batch-formula-2-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;5.98&quot;>">5.98</a></td>
</tr>
<tr><td colspan="3"><b>Other Ingredients:</b></td></tr>
<tr>
<td><a href="#Ingredient-excipient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Mannitol&quot;>">Mannitol</a></td>
<td><a href="#Ingredient-excipient1" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;>">145.0</a></td>
<td><a href="#Medication-medication-batch-formula-2-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;52.36&quot;>">52.36</a></td>
</tr>
<tr>
<td><a href="#Ingredient-excipient2" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Maize starch&quot;>">Maize starch</a></td>
<td><a href="#Ingredient-excipient2" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;>">13.8</a></td>
<td><a href="#Medication-medication-batch-formula-2-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;5.99&quot;>">5.99</a></td>
</tr>
<tr>
<td><a href="#Ingredient-excipient3" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;>">Calcium carboxymethylcellulose</a></td>
<td><a href="#Ingredient-excipient3" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;>">4.0</a></td>
<td><a href="#Medication-medication-batch-formula-2-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;1.45&quot;>">1.45</a></td>
</tr>
<tr>
<td><a href="#Ingredient-excipient4" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Magnesium stearate&quot;>">Magnesium stearate</a></td>
<td><a href="#Ingredient-excipient4" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;>">2.0</a></td>
<td><a href="#Medication-medication-batch-formula-2-unlinked" class="plainlink" title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    <strengthQuantity>
                        <value value=&quot;0.72&quot;>">0.72</a></td>
</tr>
<tr>
<td><b>Total Weight</b></td>
<td><b>180.0</b></td>
<td><b>66.5</b></td>
</tr>
</table><br style="line-height:6px;"></div>
</div>
</div>
<div class="summaryHiddenOff"></div>
<div class="indent ing summaryUnit"><a class="plainLink"><span class="bold" title="Ingredient (id: ingredient1)(fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a65)

<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <id value=&quot;ingredient1&quot;/>
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
                            <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>" id="Ingredient-ingredient1">Ingredient</span></a><span class="summaryShowsOff"> - <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072072&quot;/>
                        <display value=&quot;Active&quot;/>">Active<span class="greyOff"> [100000072072]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></span><div class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/ingredient.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/ingredient.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/ingredient.html#tt-uml">R6</a>]</span><div class="debugOff">id: ingredient1</div>
<div class="debugOff"> fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a65</div>
<div class="debugOff"><span title="
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
                <status value=&quot;active&quot;>"><span>active</span></span></div>
<div><span title="
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
                        <display value=&quot;Active&quot;/>">Active<span class="greyOff"> [100000072072]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></div>
</div>
<div class="indent ingsub"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <substance>
                    <code>
                        <reference>
                            <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>" class="summaryHiddenOff">Substance</span><div class="indent sbd summaryUnit">
<div class="debugOff"><span>Found a parent (Ingredient/code, id: ingredient1 fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a65)<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (Substance/code, id: substanceIngredient-1 fullUrl: (none))<br>which is linked to this by resource.id</span></div>
<div class="debugOff"><span>Found a parent (Substance/code, id: substanceIngredient-1 fullUrl: (none))<br>which is linked to this by resource.id</span></div><a class="plainLink"><span class="bold" title="SubstanceDefinition (id: substance1)(fullUrl: urn:uuid:4cf2cbba-33e6-1124-9bf2-1c6756380474)

<Bundle>
    <entry>
        <resource>
            <SubstanceDefinition>
                <id value=&quot;substance1&quot;/>
                <name>
                    <name value=&quot;Stelbatolol&quot;/>
                </name>" id="SubstanceDefinition-substance1">Substance</span></a><span class="summaryShowsOff"><b> - Stelbatolol</b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substancedefinition.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substancedefinition.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substancedefinition.html#tt-uml">R6</a>]</span><div class="debugOff">id: substance1</div>
<div class="debugOff"> fullUrl: urn:uuid:4cf2cbba-33e6-1124-9bf2-1c6756380474</div>
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
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
</div>
<div class="summaryHiddenOff">
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            ...
                            <display value=&quot;Stelbatolol&quot;>">Display: Stelbatolol</span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    ...
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>">Strength</span><div class="indent ingsubstr">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>">Presentation Strength: </span><span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;15.2&quot;/>
                                <unit value=&quot;mg&quot;/>">15.2 mg</span> per <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            ...
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>">1 tablet</span></span></div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
<div class="indent ing summaryUnit"><a class="plainLink"><span class="bold" title="Ingredient (id: excipient1)(fullUrl: urn:uuid:b89fd9d2-80f9-0cfb-70a1-5a6572e73a65)

<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <id value=&quot;excipient1&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>" id="Ingredient-excipient1">Ingredient</span></a><span class="summaryShowsOff"> - <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></span><div class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/ingredient.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/ingredient.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/ingredient.html#tt-uml">R6</a>]</span><div class="debugOff">id: excipient1</div>
<div class="debugOff"> fullUrl: urn:uuid:b89fd9d2-80f9-0cfb-70a1-5a6572e73a65</div>
<div class="debugOff"><span title="
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
                <status value=&quot;active&quot;>"><span>active</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></div>
</div>
<div class="indent ingsub"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>" class="summaryHiddenOff">Substance</span><div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Mannitol&quot;>">Display: Mannitol</span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    ...
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>">Strength</span><div class="indent ingsubstr">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>">Presentation Strength: </span><span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;145.0&quot;/>
                                <unit value=&quot;mg&quot;/>">145.0 mg</span> per <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            ...
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>">1 tablet</span></span></div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
<div class="indent ing summaryUnit"><a class="plainLink"><span class="bold" title="Ingredient (id: excipient2)(fullUrl: urn:uuid:b89ed9d2-81f9-0cfb-70a1-5a6572e73a65)

<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <id value=&quot;excipient2&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>" id="Ingredient-excipient2">Ingredient</span></a><span class="summaryShowsOff"> - <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></span><div class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/ingredient.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/ingredient.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/ingredient.html#tt-uml">R6</a>]</span><div class="debugOff">id: excipient2</div>
<div class="debugOff"> fullUrl: urn:uuid:b89ed9d2-81f9-0cfb-70a1-5a6572e73a65</div>
<div class="debugOff"><span title="
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
                <status value=&quot;active&quot;>"><span>active</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></div>
</div>
<div class="indent ingsub"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>" class="summaryHiddenOff">Substance</span><div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Maize starch&quot;>">Display: Maize starch</span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    ...
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>">Strength</span><div class="indent ingsubstr">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>">Presentation Strength: </span><span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;13.8&quot;/>
                                <unit value=&quot;mg&quot;/>">13.8 mg</span> per <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            ...
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>">1 tablet</span></span></div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
<div class="indent ing summaryUnit"><a class="plainLink"><span class="bold" title="Ingredient (id: excipient3)(fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a66)

<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <id value=&quot;excipient3&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>" id="Ingredient-excipient3">Ingredient</span></a><span class="summaryShowsOff"> - <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></span><div class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/ingredient.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/ingredient.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/ingredient.html#tt-uml">R6</a>]</span><div class="debugOff">id: excipient3</div>
<div class="debugOff"> fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70a1-5a6572e73a66</div>
<div class="debugOff"><span title="
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
                <status value=&quot;active&quot;>"><span>active</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></div>
</div>
<div class="indent ingsub"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>" class="summaryHiddenOff">Substance</span><div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;>">Display: Calcium carboxymethylcellulose</span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    ...
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>">Strength</span><div class="indent ingsubstr">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>">Presentation Strength: </span><span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;4.0&quot;/>
                                <unit value=&quot;mg&quot;/>">4.0 mg</span> per <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            ...
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>">1 tablet</span></span></div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
<div class="indent ing summaryUnit"><a class="plainLink"><span class="bold" title="Ingredient (id: excipient4)(fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70b1-5a6572e73a66)

<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <id value=&quot;excipient4&quot;/>
                <status value=&quot;active&quot;/>
                <for>
                    <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                </for>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>
                </role>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>
                </substance>" id="Ingredient-excipient4">Ingredient</span></a><span class="summaryShowsOff"> - <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></span><div class="summaryHiddenOff"><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/ingredient.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/ingredient.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/ingredient.html#tt-uml">R6</a>]</span><div class="debugOff">id: excipient4</div>
<div class="debugOff"> fullUrl: urn:uuid:b89ed9d2-80f9-0cfb-70b1-5a6572e73a66</div>
<div class="debugOff"><span title="
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
                <status value=&quot;active&quot;>"><span>active</span></span></div>
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>
                    </coding>">Role: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <role>
                    <coding>
                        <system value=&quot;http://hl7.org/fhir/ingredient-role&quot;/>
                        <code value=&quot;100000072082&quot;/>
                        <display value=&quot;Excipient&quot;/>">Excipient<span class="greyOff"> [100000072082]</span><span class="greyOff"> (http://hl7.org/fhir/ingredient-role)</span></span></div>
</div>
<div class="indent ingsub"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                ...
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </code>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>
                    </strength>" class="summaryHiddenOff">Substance</span><div>
<div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <code>
                        <reference>
                            <display value=&quot;Magnesium stearate&quot;>">Display: Magnesium stearate</span></div>
</div>
<div class="summaryHiddenOff">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    ...
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>
                        </presentationRatio>">Strength</span><div class="indent ingsubstr">
<div><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;/>
                                <unit value=&quot;mg&quot;/>
                            </numerator>
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>
                            </denominator>">Presentation Strength: </span><span><span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            <numerator>
                                <value value=&quot;2.0&quot;/>
                                <unit value=&quot;mg&quot;/>">2.0 mg</span> per <span title="
<Bundle>
    <entry>
        <resource>
            <Ingredient>
                <substance>
                    <strength>
                        <presentationRatio>
                            ...
                            <denominator>
                                <value value=&quot;1&quot;/>
                                <unit value=&quot;tablet&quot;/>">1 tablet</span></span></div>
</div>
</div>
</div>
</div>
<div class="summaryHiddenOff"></div>
</div>
<div class="summaryHiddenOff"></div>
<div class="indent mpdl2 summaryUnit"><span title="Medication resource extension linking back to MedicinalProductDefinition: http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq">Batch Instance</span><div class="indent med summaryUnit"><sup class="rotate-left" title="arrow indicates that this Medication resource points back to the parent MedicinalProductDefinition, instead of being linked forwards from it - via extension http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq">↸</sup><span class="debugOff">arrow indicates that this Medication resource points back to the parent MedicinalProductDefinition, instead of being linked forwards from it - via extension http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq<br></span><a class="plainLink"><span class="bold" title="Medication (id: medication-batch-formula-unlinked)(fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <id value=&quot;medication-batch-formula-unlinked&quot;/>
                <contained>
                    <Substance>
                        <id value=&quot;substanceIngredient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-2&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-3&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-4&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <code>
                    <!-- some other cases link via plandef and activity.product -->
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>
                    </extension>
                    <text value=&quot;Large Batch of Stelbatolol&quot;/>
                </code>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceIngredient-1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;true&quot;/>
                    <strengthQuantity>
                        <value value=&quot;10.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-1&quot;/>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;104.72&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-2&quot;/>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;9.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-3&quot;/>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;2.90&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-4&quot;/>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;1.44&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;722000&quot;/>
                            <unit value=&quot;tablets&quot;/>
                        </valueQuantity>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                </batch>" id="Medication-medication-batch-formula-unlinked">Medication</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/medication.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/medication.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/medication.html#tt-uml">R6</a>]</span><div class="debugOff">id: medication-batch-formula-unlinked</div><div class="debugOff"> fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070</div><span class="summaryShowsOff"><b></b></span><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <code>
                    <!-- some other cases link via plandef and activity.product -->
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>
                    </extension>
                    <text value=&quot;Large Batch of Stelbatolol&quot;/>">Code: </span><span style="white-space:normal;">Large Batch of Stelbatolol</span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <code>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>">Definition</span>: Stalbatolol (<a href="#MedicinalProductDefinition-medicinalproductdefinition-drug-product-dxpq-ex1" title="click to see target - id=medicinalproductdefinition-drug-product-dxpq-ex1">MedicinalProductDefinition</a>)<span class="debugOff"> id: medicinalproductdefinition-drug-product-dxpq-ex1</span></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceIngredient-1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;true&quot;/>
                    <strengthQuantity>
                        <value value=&quot;10.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceIngredient-1)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceIngredient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-unlinked-contained-Substance-substanceIngredient-1">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceIngredient-1</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>">Definition: </span>Stelbatolol (<a href="#SubstanceDefinition-substance1" title="click to see target - id=substance1">SubstanceDefinition</a>)<span class="debugOff"> id: substance1</span></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;true&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;true&quot;>"><span>true</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;10.98&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;10.98&quot;/>
                        <unit value=&quot;kg&quot;/>">10.98 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-1&quot;/>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;104.72&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-1)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-unlinked-contained-Substance-substanceExcipient-1">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-1</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;>">Display: Mannitol</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;104.72&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;104.72&quot;/>
                        <unit value=&quot;kg&quot;/>">104.72 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-2&quot;/>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;9.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-2)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-2&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-unlinked-contained-Substance-substanceExcipient-2">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-2</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;>">Display: Maize starch</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;9.98&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;9.98&quot;/>
                        <unit value=&quot;kg&quot;/>">9.98 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-3&quot;/>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;2.90&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-3)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-3&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-unlinked-contained-Substance-substanceExcipient-3">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-3</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;>">Display: Calcium carboxymethylcellulose</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;2.90&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;2.90&quot;/>
                        <unit value=&quot;kg&quot;/>">2.90 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-4&quot;/>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;1.44&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-4)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-4&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-unlinked-contained-Substance-substanceExcipient-4">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-4</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;>">Display: Magnesium stearate</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;1.44&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;1.44&quot;/>
                        <unit value=&quot;kg&quot;/>">1.44 kg</span></div></div><div class="summaryHiddenOff"><div class="indent medl2 summaryUnit"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;722000&quot;/>
                            <unit value=&quot;tablets&quot;/>
                        </valueQuantity>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>">Batch</span><div class="summaryHiddenOff"><div class="indent medl3"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    ...
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>">Manufacturing</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>">Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;130&quot;/>
                                <unit value=&quot;kg&quot;/>">130 kg</span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;722000&quot;/>
                            <unit value=&quot;tablets&quot;/>">Items: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;722000&quot;/>
                            <unit value=&quot;tablets&quot;/>">722000 tablets</span></div></div></div></div></div></div><div class="indent med summaryUnit"><sup class="rotate-left" title="arrow indicates that this Medication resource points back to the parent MedicinalProductDefinition, instead of being linked forwards from it - via extension http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq">↸</sup><span class="debugOff">arrow indicates that this Medication resource points back to the parent MedicinalProductDefinition, instead of being linked forwards from it - via extension http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq<br></span><a class="plainLink"><span class="bold" title="Medication (id: medication-batch-formula-2-unlinked)(fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <id value=&quot;medication-batch-formula-2-unlinked&quot;/>
                <contained>
                    <Substance>
                        <id value=&quot;substanceIngredient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-2&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-3&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-4&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>
                        </code>
                    </Substance>
                </contained>
                <code>
                    <!-- some other cases link via plandef and activity.product -->
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>
                    </extension>
                    <text value=&quot;Small Batch of Stelbatolol&quot;/>
                </code>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceIngredient-1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;true&quot;/>
                    <strengthQuantity>
                        <value value=&quot;5.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-1&quot;/>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;52.36&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-2&quot;/>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;5.99&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-3&quot;/>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;1.45&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-4&quot;/>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;0.72&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>
                </ingredient>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;371000&quot;/>
                            <unit value=&quot;tablets&quot;/>
                        </valueQuantity>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>
                </batch>" id="Medication-medication-batch-formula-2-unlinked">Medication</span></a><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/medication.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/medication.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/medication.html#tt-uml">R6</a>]</span><div class="debugOff">id: medication-batch-formula-2-unlinked</div><div class="debugOff"> fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071</div><span class="summaryShowsOff"><b></b></span><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <code>
                    <!-- some other cases link via plandef and activity.product -->
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>
                    </extension>
                    <text value=&quot;Small Batch of Stelbatolol&quot;/>">Code: </span><span style="white-space:normal;">Small Batch of Stelbatolol</span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <code>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-medication-definition-pq&quot;>
                        <valueReference>
                            <reference value=&quot;MedicinalProductDefinition/medicinalproductdefinition-drug-product-dxpq-ex1&quot;/>
                        </valueReference>">Definition</span>: Stalbatolol (<a href="#MedicinalProductDefinition-medicinalproductdefinition-drug-product-dxpq-ex1" title="click to see target - id=medicinalproductdefinition-drug-product-dxpq-ex1">MedicinalProductDefinition</a>)<span class="debugOff"> id: medicinalproductdefinition-drug-product-dxpq-ex1</span></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceIngredient-1&quot;/>
                            <display value=&quot;Stelbatolol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;true&quot;/>
                    <strengthQuantity>
                        <value value=&quot;5.98&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceIngredient-1)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceIngredient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-2-unlinked-contained-Substance-substanceIngredient-1">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceIngredient-1</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <reference value=&quot;SubstanceDefinition/substance1&quot;/>
                            </reference>">Definition: </span>Stelbatolol (<a href="#SubstanceDefinition-substance1" title="click to see target - id=substance1">SubstanceDefinition</a>)<span class="debugOff"> id: substance1</span></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;true&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;true&quot;>"><span>true</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;5.98&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;5.98&quot;/>
                        <unit value=&quot;kg&quot;/>">5.98 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-1&quot;/>
                            <display value=&quot;Mannitol&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;52.36&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-1)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-1&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-2-unlinked-contained-Substance-substanceExcipient-1">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-1</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Mannitol&quot;>">Display: Mannitol</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;52.36&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;52.36&quot;/>
                        <unit value=&quot;kg&quot;/>">52.36 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-2&quot;/>
                            <display value=&quot;Maize starch&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;5.99&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-2)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-2&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-2-unlinked-contained-Substance-substanceExcipient-2">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-2</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Maize starch&quot;>">Display: Maize starch</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;5.99&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;5.99&quot;/>
                        <unit value=&quot;kg&quot;/>">5.99 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-3&quot;/>
                            <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;1.45&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-3)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-3&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-2-unlinked-contained-Substance-substanceExcipient-3">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-3</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Calcium carboxymethylcellulose&quot;>">Display: Calcium carboxymethylcellulose</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;1.45&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;1.45&quot;/>
                        <unit value=&quot;kg&quot;/>">1.45 kg</span></div></div><div class="indent medl2"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <ingredient>
                    <item>
                        <reference>
                            <reference value=&quot;#substanceExcipient-4&quot;/>
                            <display value=&quot;Magnesium stearate&quot;/>
                        </reference>
                    </item>
                    <isActive value=&quot;false&quot;/>
                    <strengthQuantity>
                        <value value=&quot;0.72&quot;/>
                        <unit value=&quot;kg&quot;/>
                    </strengthQuantity>">Ingredient</span><div class="indent sbd summaryUnit"><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11070)<br>which is linked to this by contained resource.id</span></div><div class="debugOff"><span>Found a parent (Medication/item, id: medication-batch-formula-2-unlinked fullUrl: urn:uuid:bf17176f-9779-180b-5c59-e58cddc11071)<br>which is linked to this by contained resource.id</span></div><a class="plainLink"><span class="bold" title="Substance (id: substanceExcipient-4)

<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <id value=&quot;substanceExcipient-4&quot;/>
                        <instance value=&quot;false&quot;/>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>
                        </code>" id="medication-batch-formula-2-unlinked-contained-Substance-substanceExcipient-4">Substance</span></a><span class="summaryShowsOff"><b></b></span><span class="debugOff"> [documentation <a target="_blank" href="http://hl7.org/fhir/R4/substance.html#tt-uml">R4</a> <a target="_blank" href="http://hl7.org/fhir/substance.html#tt-uml">R5</a> <a target="_blank" href="http://build.fhir.org/substance.html#tt-uml">R6</a>]</span><div class="debugOff">id: substanceExcipient-4</div><div class="debugOff"> fullUrl: (none)</div><div class="summaryHiddenOff"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>">Instance: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <instance value=&quot;false&quot;>"><span>false</span></span></div><div><div class="indent sbddetails"><div></div><span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        ...
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;/>
                            </reference>">Definition: </span><div><div class="indent org"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <contained>
                    <Substance>
                        <code>
                            <reference>
                                <display value=&quot;Magnesium stearate&quot;>">Display: Magnesium stearate</span></div></div></span></div></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div><div class="summaryHiddenOff"></div></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>">Active ingredient: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <isActive value=&quot;false&quot;>"><span>false</span></span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;0.72&quot;/>
                        <unit value=&quot;kg&quot;/>">Strength - Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <ingredient>
                    ...
                    <strengthQuantity>
                        <value value=&quot;0.72&quot;/>
                        <unit value=&quot;kg&quot;/>">0.72 kg</span></div></div><div class="summaryHiddenOff"><div class="indent medl2 summaryUnit"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                ...
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;371000&quot;/>
                            <unit value=&quot;tablets&quot;/>
                        </valueQuantity>
                    </extension>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>
                    </extension>">Batch</span><div class="summaryHiddenOff"><div class="indent medl3"><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    ...
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>
                            </valueQuantity>
                        </extension>">Manufacturing</span><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>">Quantity: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/StructureDefinition/medication-manufacturingBatch&quot;>
                        <extension url=&quot;batchQuantity&quot;>
                            <valueQuantity>
                                <value value=&quot;65&quot;/>
                                <unit value=&quot;kg&quot;/>">65 kg</span></div><div><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;371000&quot;/>
                            <unit value=&quot;tablets&quot;/>">Items: </span><span title="
<Bundle>
    <entry>
        <resource>
            <Medication>
                <batch>
                    <extension url=&quot;http://hl7.org/fhir/uv/pharm-quality/StructureDefinition/Extension-batch-number-of-items-pq&quot;>
                        <valueQuantity>
                            <value value=&quot;371000&quot;/>
                            <unit value=&quot;tablets&quot;/>">371000 tablets</span></div></div></div></div></div></div>
</div>
<div></div>
</div>
<div class="summaryHiddenOff"></div>
<div class="summaryHiddenOff"></div>
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
		First resource in bundle:MedicinalProductDefinition
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

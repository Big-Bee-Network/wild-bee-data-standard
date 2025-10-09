# *The Wild Bee Data Standard* List of Terms

## Introduction to *The Wild Bee Data Standard*

<i>The Wild Bee Data Standard</i> term list contains 75 Darwin Core terms, divided into 26 Core terms, 22 Recommended terms, and 27 Optional terms. We present these terms by the requirement tier in Darwin Core categorical order: Core terms are those that must be collected and provided with all current and future wild bee occurrence data to ensure data quality; these are listed first, followed by recommended terms that should be provided if collected and optional terms that can be provided if collected (Box 1). For each term, we provide a definition, rationale for use, instructions for use, examples for use with wild bee occurrence data, and a link to the Darwin Core reference guide for that term (Table 1). 

<table>
	<thead>
		<tr>
			<th colspan="2">Box 1. Organizational structure of <i>The Wild Bee Standard</i> term list.</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>The Wild Bee Standard contains 75 Darwin Core terms within three tiers of data collection and reporting:
			<ol>
			<li>Core: these 26 terms must be collected and provided.</li>
			<li>Recommended: these 22 terms should be provided if the information was collected.</li>
			<li>Optional: these 27 terms can be provided if the information was collected, depending on one’s objective(s).</li>
			</ol> Within these tiers, we present terms in Darwin Core categorical order. The Darwin Core categories used in The Wild Bee Data Standard are: <ul class="list-group list-group-flush">
            <li class="list-group-item">Record-level: This category contains terms that are generic in that they might apply to any type of record in a dataset.</li>
            <li class="list-group-item">Occurrence: data that describe the existence of an organism at a particular place at a particular time.</li>
            <li class="list-group-item">MaterialEntity: data that describe an entity that can be identified, exists for some period of time, and consists in whole or in part of physical matter while it exists.</li>
            <li class="list-group-item">Event: data that describe an action that occurs at some location during some time.</li>
			<li class="list-group-item">Location: data that describe a spatial region or named place.</li>
			<li class="list-group-item">Identification: data that describe a taxonomic determination.</li>
			<li class="list-group-item">Taxon: data that describe a group of organisms.</li>
            </ul>For more information on these categories and a full Darwin Core term list, please visit <a href="https://dwc.tdwg.org/terms/">https://dwc.tdwg.org/terms/</a>.
			</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2">Table 1. The format for a term description in <i>The Wild Bee Data Standard</i>.</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term name</td>
			<td>The name of the Darwin Core term.</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The name (or acronym) in use by the institution having custody of the object(s) or information referred to in the record.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Reason for using the term to describe wild bee occurrences.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Whether the term is core, recommended, or optional to use (Box 1).</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Instructions for using the term to align with <i>The Wild Bee Data Standard</i>. <ul class="list-group list-group-flush">
            <li class="list-group-item">Controlled vocabulary list:</li>
            <ul><li class="list-group-item">The list of allowable entries for terms with a controlled vocabulary.</li></ul>
            </ul></td>
		</tr>
		<tr>
			<td>Example(s)</td>
			<td>Practical example(s) of information that would be entered into a field for that term.</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>Most terms are relevant to <a href="https://journals.ku.edu/melittology/issue/view/2768">all Bee Monitoring RCN protocols</a>.</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td>Link to the term entry in the Darwin Core quick reference guide (<a href="https://dwc.tdwg.org/terms/">https://dwc.tdwg.org/terms/</a>).</td>
		</tr>
	</tbody>
</table>

## Term List Index

### Core terms

#### Record level

[dwc:institutionCode](#dwc_institutionCode) |
[dwc:basisOfRecord](#dwc_basisOfRecord) |
[dwc:informationWithheld](#dwc_informationWithheld) 

#### Occurrence

[dwc:occurrenceID](#dwc_occurrenceID) |
[dwc:catalogNumber](#dwc_catalogNumber) |
[dwc:recordedBy](#dwc_recordedBy) |
[dwc:individualCount](#dwc_individualCount) |
[dwc:occurrenceStatus](#dwc_occurrenceStatus) 

#### Event

[dwc:eventDate](#dwc_eventDate) |
[dwc:eventTime](#dwc_eventTime) |
[dwc:year](#dwc_year) |
[dwc:month](#dwc_month) |
[dwc:day](#dwc_day) |
[dwc:samplingProtocol](#dwc_samplingProtocol) |
[dwc:sampleSizeValue](#dwc_sampleSizeValue) |
[dwc:sampleSizeUnit](#dwc_sampleSizeUnit) |
[dwc:samplingEffort](#dwc_samplingEffort) 

#### Location

[dwc:country](#dwc_country) |
[dwc:stateProvince](#dwc_stateProvince) |
[dwc:decimalLatitude](#dwc_decimalLatitude) |
[dwc:decimalLongitude](#dwc_decimalLongitude) |
[dwc:coordinateUncertaintyInMeters](#dwc_coordinateUncertaintyInMeters)

#### Identification

[dwc:identifiedBy](#dwc_identifiedBy)

#### Taxon

[dwc:scientificName](#dwc_scientificName) |
[dwc:genus](#dwc_genus) |
[dwc:specificEpithet](#dwc_specificEpithet)

### Recommended terms

#### Record level

[dcterms:license](#dcterms_license) |
[dwc:institutionID](#dwc_institutionID) |
[dwc:collectionID](#dwc_collectionID) |
[dwc:collectionCode](#dwc_collectionCode) 

#### Occurrence

[dwc:recordedByID](#dwc_recordedByID) |
[dwc:sex](#dwc_sex) |
[dwc:associatedTaxa](#dwc_associatedTaxa) 

#### Material Entity

[dwc:disposition](#dwc_disposition)

#### Event

[dwc:eventID](#dwc_eventID) |
[dwc:eventRemarks](#dwc_eventRemarks) 

#### Location

[dwc:locationID](#dwc_locationID) |
[dwc:geodeticDatum](#dwc_geodeticDatum)

#### Identification

[dwc:verbatimIdentification](#dwc_verbatimIdentification) |
[dwc:identificationQualifier](#dwc_identificationQualifier) |
[dwc:identifiedByID](#dwc_identifiedByID) |
[dwc:dateIdentified](#dwc_dateIdentified) |
[dwc:identificationReferences](#dwc_identificationReferences) 

#### Taxon

[dwc:taxonID](#dwc_taxonID) |
[dwc:nameAccordingTo](#dwc_nameAccordingTo) |
[dwc:family](#dwc_family) |
[dwc:infraspecificEpithet](#dwc_infraspecificEpithet) |
[dwc:scientificNameAuthorship](#dwc_scientificNameAuthorship)

### Optional terms

#### Record level

[dcterms:rightsHolder](#dcterms_rightsHolder) |
[dwc:dynamicProperties](#dwc_dynamicProperties) 

#### Occurrence

[dwc:lifeStage](#dwc_lifeStage) |
[dwc:caste](#dwc_caste) |
[dwc:behavior](#dwc_behavior) |
[dwc:vitality](#dwc_vitality) |
[dwc:associatedMedia](#dwc_associatedMedia) |
[dwc:associatedOccurrences](#dwc_associatedOccurrences) |
[dwc:occurrenceRemarks](#dwc_occurrenceRemarks) 

#### Material Entity

[dwc:preparations](#dwc_preparations) |
[dwc:associatedSequences](#dwc_associatedSequences) |
[dwc:materialEntityRemarks](#dwc_materialEntityRemarks)

#### Event

[dwc:fieldNumber](#dwc_fieldNumber) |
[dwc:habitat](#dwc_habitat)

#### Location

[dwc:county](#dwc_county) |
[dwc:locality](#dwc_locality) |
[dwc:verbatimElevation](#dwc_verbatimElevation) |
[dwc:coordinatePrecision](#dwc_coordinatePrecision) |
[dwc:georeferencedBy](#dwc_georeferencedBy) |
[dwc:georeferenceSources](#dwc_georeferenceSources) 

#### Identification

[dwc:typeStatus](#dwc_typeStatus) |
[dwc:identificationRemarks](#dwc_identificationRemarks)

#### Taxon

[dwc:namePublishedIn](#dwc_namePublishedIn) |
[dwc:tribe](#dwc_tribe) |
[dwc:subgenus](#dwc_subgenus) |
[dwc:taxonRank](#dwc_taxonRank) |
[dwc:vernacularName](#dwc_vernacularName) 

## Term List Details

### Core terms

#### Record level

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_institutionCode"></a>Term Name: institutionCode</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The name (or acronym) in use by the institution having custody of the object(s) or information referred to in the record.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Indicates the institution that holds or curates the specimen or observation record, which may lead to a point of contact for more information about an occurrence.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Provide a name or acronym for the institution or organization that houses the specimen or coordinated the observation. If the institution or organization is registered in the <a href="https://scientific-collections.gbif.org/)"> Global Registry of Scientific Collections</a>, please use the code listed there. For lab collections managed in-house, please provide the name of the lab.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
				<li class="list-group-item">USDA-ARS</li>
            			<li class="list-group-item">UNHC</li>
            			<li class="list-group-item">iNaturalist</li>
				<li class="list-group-item">AMNH</li>
            			<li class="list-group-item">Woodard Lab</li>
            		</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href=" https://dwc.tdwg.org/terms/#dwc:institutionCode "> https://dwc.tdwg.org/terms/#dwc:institutionCode </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_basisOfRecord"></a>Term Name: basisOfRecord</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The specific nature of the data record.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>This term is required for publication to GBIF. <b>dwc:basisOfRecord</b> describes the type of occurrence record to indicate whether it includes a specimen, an observation, tissue material, or is gathered from the literature. This is essential context for interpretation.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. <i>The Wild Bee Data Standard</i> follows the GBIF vocabulary for the basis of record. <ul class="list-group list-group-flush">
				<li class="list-group-item">Controlled vocabulary list for <b>dwc:basisOfRecord</b>:</li>
					<ul><li class="list-group-item">PreservedSpecimen, to describe labeled wild bee specimens preserved on pins or in vials.</li>
					<li class="list-group-item">HumanObservation, to describe wild bees observed in the field and captured in photographs taken in person when using non-lethal sampling methods.</li>
					<li class="list-group-item">MachineObservation, to describe wild bees captured in photographs taken via camera trap when using non-lethal sampling methods.</li>
					<li class="list-group-item">MaterialEntity, taken from the Darwin Core vocabulary for <b>dwc:basisOfRecord</b> to describe genetic or pathogen material.</li>
					<li class="list-group-item">MachineCitation, to describe occurrences gathered from published literature.</li>
				</ul>
            		</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>PreservedSpecimen, HumanObservation</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:basisOfRecord"> https://dwc.tdwg.org/terms/#dwc:basisOfRecord</a>, <a href="https://docs.gbif.org/course-data-use/en/basis-of-record.html"> https://docs.gbif.org/course-data-use/en/basis-of-record.html</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_informationWithheld"></a>Term Name: informationWithheld</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Additional information that exists, but that has not been shared in the given record.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>If any core information is not shared, the type of information and the rationale for not sharing it must be provided. In particular, if the exact location of the record is masked, this cell must indicate that and describe why masking occurred.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core, if applicable (see rationale).</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This is a text-based term that allows any word-based entry.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
				<li class="list-group-item">Exact location removed to mask for endangered/threatened/rare bee or host plant species or owing to private land ownership.</li>
            			<li class="list-group-item">Decimal latitude/longitude rounded to obscure exact location because it is private land.</li>
            		</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href=" https://dwc.tdwg.org/terms/#dwc:informationWithheld">  https://dwc.tdwg.org/terms/#dwc:informationWithheld</a></td>
		</tr>
	</tbody>
</table>

#### Occurrence

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_occurrenceID"></a>Term Name: occurrenceID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A unique identifier for the occurrence.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>This term is required for publication to GBIF. Unique identifiers simplify and standardize data management and sharing practices.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>We advise creating universally unique identifiers, or UUIDs, to serve as <b>dwc:occurrenceID</b>s. These can be created using R packages, Excel macros, or website applications. While GBIF will not generate these for you, consider that uploading to a CMS automatically creates <b>dwc:occurrenceID</b>s for each record. </td>
		</tr>
		<tr>
			<td>Example</td>
			<td>8d13f958-10fa-490a-8c32-5938be9d2037</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:occurrenceID"> https://dwc.tdwg.org/terms/#dwc:occurrenceID</a>, <a href="https://www.gbif.org/data-quality-requirements-occurrences#dcOccurrenceID">https://www.gbif.org/data-quality-requirements-occurrences#dcOccurrenceID</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_catalogNumber"></a>Term Name: catalogNumber</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A unique identifier within a dataset or collection.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Physical specimens accessioned into a collection will have a unique ID assigned to them; that number gets reported through <b>dwc:catalogNumber</b> to reference back to the original dataset. </td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core, if applicable (see rationale).</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Use this term to share the unique ID of a record or specimen in an original dataset or collection. To improve uniqueness, human-readability, and machine interpretation in large, multi-institution datasets, please include a sufficient amount of both letters and numbers when creating these IDs.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>BBSL319283, AMNH PBI 82341, UNH-150861</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/list/#dwc_catalogNumber "> https://dwc.tdwg.org/list/#dwc_catalogNumber  </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_recordedBy"></a>Term Name: recordedBy</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of names of people, groups, or organizations responsible for recording the original occurrence. This is a synonym of “Collector.”</td>
		</tr>
       	 	<tr>
			<td>Rationale</td>
			<td>Providing the names of the collector or observer creates a potential point of contact for more information regarding an occurrence.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Use full names (First [Middle Initial, if provided] Last) whenever possible. When multiple collectors are working simultaneously, list the specimens collected by each collector individually. If that is not possible, the primary collector or observer should be listed first. Separate the values in a list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell. Please be sure to record the number of collectors in <b>dwc:samplingEffort</b>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
            			<li class="list-group-item">For one collector:</li>
					<ul><li class="list-group-item">Frank D. Parker</li>
				</ul>
				<li class="list-group-item">For two collectors:</li>
					<ul><li class="list-group-item">Olivia J. Messinger | Terry L. Griswold</li>
				</ul>
            		</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:recordedBy "> https://dwc.tdwg.org/terms/#dwc:recordedBy</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_individualCount"></a>Term Name: individualCount</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The number of individual organisms present at the time of the occurrence.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Most records of wild bee occurrences represent one bee. This indicates a detection of a bee, but it is important in many cases to also indicate non-detections of focal bee species, represented as zeros.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Report the number of individual organisms counted in the occurrence. Only whole numbers are permitted. When sampling for focal species (Otto et al., 2024), if they are not found at a sampling site, use this term to report non-detections.
			<ul class="list-group list-group-flush">
				<li class="list-group-item">A 0 entry for <b>dwc:individualCount</b> represents a non-detection.</li>
				<li class="list-group-item">Most records will have an entry of 1 for <b>dwc:individualCount</b>, as most records correspond to an observation or collection (a detection) of a single organism.					</li>
				<li class="list-group-item">Entries larger than 1 are possible in some cases; for example:</li>
				<ul><li class="list-group-item">If a large number of the same species is collected, but only a subset of specimens of that species are preserved.</li>
				<li class="list-group-item">If multiple bees of the same species are in a photo observation on a plant.</li>
				<li class="list-group-item">If multiple bees of the same species are observed at the same site, but a photo voucher is created for only one of those bees.</li>
				</ul>
			</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>0, 1, 2, etc.</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All, but particularly important for the occupancy of focal species protocol (Otto et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:individualCount"> https://dwc.tdwg.org/terms/#dwc:individualCount</a>, <a href="https://www.gbif.org/data-quality-requirements-occurrences#dcCount"> https://www.gbif.org/data-quality-requirements-occurrences#dcCount </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_occurrenceStatus"></a>Term Name: occurrenceStatus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A statement about the presence or absence of a taxon at a location.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>This term indicates if a species was detected or not detected during a sampling event and is particularly important to report when conducting occupancy surveys. Providing both detections and non-detections are crucial for occupancy modeling.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Although the Darwin Core standard recommends the use of “present” and “absent” to designate occurrence status, we suggest observers instead use “detected” and “notDetected” when recording results from sampling events.  Absence is seldom known with certainty and we recommend avoiding the use of this term during data collection.
			<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:occurrenceStatus</b>:</li>
				<ul><li class="list-group-item">detected</li>
				<li class="list-group-item">notDetected</li>
				</ul>
			</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>detected, notDetected</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All, but particularly important for the occupancy of focal species protocol (Otto et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:occurrenceStatus "> https://dwc.tdwg.org/terms/#dwc:occurrenceStatus </a></td>
		</tr>
	</tbody>
</table>

#### Event

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_eventDate"></a>Term Name: eventDate</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The date-time or interval during which a sampling event occurred.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>This term is required for publication to GBIF. Providing a collection or observation date provides essential context for interpreting an occurrence.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Recommended best practice is to use a date that conforms to ISO 8601-1:2019. Provide the date or dates sampling occurred in YYYY-MM-DD format. If reporting an interval of dates, separate the dates with a slash ( / ). Please be sure to provide accompanying sampling protocol and effort information in the terms <b>dwc:samplingProtocol</b>, <b>dwc:sampleSizeValue</b>, <b>dwc:sampleSizeUnit</b>, and <b>dwc:samplingEffort</b>.
			</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
				<li class="list-group-item">2015-08-14</li>
					<ul><li class="list-group-item">For single day sampling.</li>
				</ul>
				<li class="list-group-item">2015-08-14T16:00:00/2015-08-15T16:00:00</li>
					<ul><li class="list-group-item">For sampling over a maximum 24-hour period that spans two dates. This is interpreted as: collections started on August 14, 2015 at 4pm local time and ended August 15, 2015 at 4pm local time. Note that in this case, <b>dwc:eventTime</b> does not need to be provided, but can be, as the sampling time interval is included in <b>dwc:eventDate</b>.</li>
				</ul>
				</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:eventDate"> https://dwc.tdwg.org/terms/#dwc:eventDate</a>, <a href="https://www.gbif.org/data-quality-requirements-occurrences#dcEventDate "> https://www.gbif.org/data-quality-requirements-occurrences#dcEventDate</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_eventTime"></a>Term Name: eventTime</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The time or interval during which a sampling event occurred.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>This term is used in conjunction with <b>dwc:eventDate</b> to clarify the sampling time interval and is best used when sampling occurs on a single day.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Recommended best practice is to use a time that conforms to ISO 8601-1:2019. Report in local time. Report the total sampling time interval, covering the start and end time of either passive trap deployment or active sampling. The correct format is start time/end time. Use <b>dwc:samplingEffort</b> to report the duration of sampling time in hours, person-hours, or decimals of hours or person-hours. Please be sure to provide accompanying sampling protocol and effort information in the terms <b>dwc:samplingProtocol</b>, <b>dwc:sampleSizeValue</b>, <b>dwc:sampleSizeUnit</b>, and <b>dwc:samplingEffort</b>.
			</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
				<li class="list-group-item">09:00/15:00, 09:30/09:40, 11:50/12:00, 14:15/14:25</li>
					<ul><li class="list-group-item">For a 24-hour sampling time interval, please use <b>dwc:eventDate</b> instead.</li>
				</ul>
				<li class="list-group-item">08:30/08:30</li>
					<ul><li class="list-group-item">If choosing to report a 24-hour sampling time interval.</li>
				</ul>
			</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:eventTime"> https://dwc.tdwg.org/terms/#dwc:eventTime</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_year"></a>Term Name: year</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The four-digit year in which the sampling event occurred, according to the Common Era Calendar.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Separating the full <b>dwc:eventDate</b> into year, month, and day simplifies data entry and sorting for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This is a numeric field. Enter the four-digit year the sampling event occurred.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>1965, 2013</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:year"> https://dwc.tdwg.org/terms/#dwc:year</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_month"></a>Term Name: month</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The integer month in which the sampling event occurred.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Separating the full <b>dwc:eventDate</b> into year, month, and day simplifies data entry and sorting for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This is a numeric field. Enter the one or two-digit month when the sampling event occurred. Bee communities vary widely by month.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>1, 10</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:month"> https://dwc.tdwg.org/terms/#dwc:month</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_day"></a>Term Name: day</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The integer day of the month on which the sampling event occurred.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Separating the full <b>dwc:eventDate</b> into year, month, and day simplifies data entry and sorting for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core, if applicable (see How to use).</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This is a numeric field. Enter the one or two-digit day of the month when the sampling event occurred. If sampling occurred over multiple days; i.e., passive traps were used, do not use this term, as it only records one day. The terms <b>dwc:year</b> and <b>dwc:month</b> should still be used if sampling occurred over multiple days.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>8, 23</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:day "> https://dwc.tdwg.org/terms/#dwc:day</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_samplingProtocol"></a>Term Name: samplingProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The names of, references to, or descriptions of the methods or protocols used during a sampling event.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Describing the sampling method(s) used is a requirement for some types of species distribution models. It also improves replicability of study methods and provides insights into life-history that may be useful for recollection.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term uses two controlled vocabularies; one for active sampling methods and one for passive sampling methods. Additionally, some of the active sampling entries are provided using key:value pairs. Select the sampling method used from the list of allowable entries. <ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary lists for <b>dwc:samplingProtocol</b>:</li>
				<ul><li class="list-group-item">Active sampling: hand net:lethal, hand net:released, sweep net:lethal, sweep net:released, vial:lethal, vial:released, photograph, visual observation</li>
				<li class="list-group-item">Passive sampling: bowl traps, glycol cups, malaise traps, vane traps</li>
				</ul>
				</ul>
				In addition to providing the sampling method(s) following the controlled vocabulary list, cite the source of your protocol following a vertical bar space character ( | )
				<ul><li class="list-group-item">Cariveau, D.P., Hung, K.-L. J., Williams, N.M., Inouye, D.W., Burns, C.T., Lane, I., Levenson, H.K., Du Clos, B., Woodard, S.H. 2024. Standardized protocol for collecting plant-pollinator interaction data. Journal of Melittology. 123(x): 1–x.</li>
				<li class="list-group-item">Levenson, H.K., O. Messinger Carril, N.E. Turley, C. Maffei, G. LeBuhn, T. Griswold, N.M. Williams, K.L.J. Hung, R.E. Irwin, B. Du Clos, & S.H. Woodard. 2024b. Standardized protocol for collecting community-level bee data. Journal of Melittology 123(3): 1–x.</li>
				<li class="list-group-item">López-Uribe, M.M., J.P. Strange, L. Whiteman, B.N. Danforth, S. Jha, M. Branstetter, J.B.U. Koch, H.K. Levenson, B. Du Clos, & S.H. Woodard. 2024. Standardized protocols for collecting bee samples for genetic or genomic data. Journal of Melittology 123(6): 1–x.</li>
				<li class="list-group-item">Otto, C.R.V., L.L. Bailey, T.A. Smith, E.C. Evans, I. Pearse, S. Killingsworth, B. Du Clos, S. Jepsen, & S.H. Woodard. 2024. Estimating occupancy of focal bee species. Journal of Melittology 123(5): 1–x.</li>
				<li class="list-group-item">Strange, J.P., M.M. López-Uribe, L. Whiteman, B.N. Danforth, S. Jha, H.K. Levenson, B. Du Clos, J.B.U. Koch, & S.H. Woodard. 2024. Standardized protocols for collecting bee samples for pathogen data. Journal of Melittology 123(7): 1–x.</li>
				<li class="list-group-item">LeBuhn, G., T. Griswold, R. Minckley, S. Droege, T. Roulston, J. Cane, F. Parker, S. Buchmann, V. Tepedino, N. Williams, C. Kremen, & O. Messinger. 2003. A standardized method for monitoring bee populations—the bee inventory (BI) plot. Available from <a href="https://www.nativebeemonitoring.org/s/Bee-Plot-2003.pdf ">https://www.nativebeemonitoring.org/s/Bee-Plot-2003.pdf</a></li>
				<li class="list-group-item">A Collective and Ongoing Collaborative Effort by Those Who Love to Study Bees in North America. (2024). The Very Handy Bee Manual (2.0). Zenodo. <a href="https://doi.org/10.5281/zenodo.12812754">https://doi.org/10.5281/zenodo.12812754 </a></li>
				<li class="list-group-item">Maffei, C., Lent, S., Lane, I., Jones, P., and K. Dillon. 2025. National Protocol Framework for the Inventory and Monitoring of Bees. Version 3.0. Inventory and Monitoring, National Wildlife Refuge System, U.S. Fish and Wildlife Service, Fort Collins, Colorado. <a href="https://iris.fws.gov/APPS/ServCat/Reference/Profile/179113">https://iris.fws.gov/APPS/ServCat/Reference/Profile/179113</a></li>
				<li class="list-group-item">Packer, L., & G. Darla-West. (2021). Bees: How and Why to Sample Them. In: Santos, J.C., Fernandes, G.W. (eds) Measuring Arthropod Biodiversity. Springer, Cham. <a href="https://doi.org/10.1007/978-3-030-53226-0_3"> https://doi.org/10.1007/978-3-030-53226-0_3 </a></li>
				<li class="list-group-item">Other protocols used can be cited.</li>
				<li class="list-group-item">Papers published that describe the protocol used to collect the specimen can be cited.</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">bowl trap | The Very Handy Bee Manual (A Collective 2024) <a href="https://doi.org/10.5281/zenodo.12812754">https://doi.org/10.5281/zenodo.12812754 </a> </li>
			<li class="list-group-item">hand net:lethal | Maffei et al., (2025) <a href="https://iris.fws.gov/APPS/ServCat/Reference/Profile/179113">https://iris.fws.gov/APPS/ServCat/Reference/Profile/179113</a></li>
			</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:samplingProtocol"> https://dwc.tdwg.org/terms/#dwc:samplingProtocol</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_sampleSizeValue"></a>Term Name: sampleSizeValue</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A numeric value for a measurement of the size (time duration, length, area, or volume) of a sample in a sampling event.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Allows for full reporting of sampling effort, supporting analyses of species distribution. This term is used to describe the number of traps used when passive sampling or the number of personnel conducting active sampling in a sampling event.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Use of this term varies with active or passive sampling methods, but it must always be used with <b>dwc:sampleSizeUnit</b>. Provide a number of sampling units specific to passive samples (number of traps collected) or active samples (number of collectors or observers).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>1, 25</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:sampleSizeValue"> https://dwc.tdwg.org/terms/#dwc:sampleSizeValue</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_sampleSizeUnit"></a>Term Name: sampleSizeUnit</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A unit of measurement of the size of a sample in a sampling event.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Allows for full reporting of sampling effort, supporting analyses of species distribution. This term is used to describe the type of equipment used in passive sampling or the role of personnel conducting active sampling during a sampling event.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Use of this term varies with active or passive sampling methods, but it must always be used with <b>dwc:sampleSizeValue</b>. Provide a sampling unit specific to passive samples ([type of] traps collected) or active samples (collectors or observers)<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:sampleSizeUnit</b>:</li>
				<ul><li class="list-group-item">bowl, cup, Malaise, or vane traps collected</li>
				<li class="list-group-item">collectors</li>
				<li class="list-group-item">observers</li>
				</ul>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">bowl traps collected </li>
			<li class="list-group-item">cup traps collected</li>
			<li class="list-group-item">observers</li>
			</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:sampleSizeUnit"> https://dwc.tdwg.org/terms/#dwc:sampleSizeUnit </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_samplingEffort"></a>Term Name: samplingEffort</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The amount of effort expended during a sampling event.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Describing the sampling effort expended to obtain a species observation is a requirement for some types of species distribution models.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term is used to report both sampling area (in metric units) and duration of sampling time. Report duration of passive sampling time in hours or decimals of hours. Report duration of active sampling time in person-hours (i.e., the amount of work done by one person in one hour) or decimals of person-hours. If reporting both sampling area and duration of sampling time, separate them with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell. Use <b>dwc:eventDate</b> to report the start and end times of sampling.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">100 m transect, 1 ha, 100m2</li>
				<ul><li class="list-group-item">For reporting amount of area sampled.</li>
				</ul>
			<li class="list-group-item">6 hours, 24 hours</li>
				<ul><li class="list-group-item">When recording duration of passive sampling.</li>
				</ul>
			<li class="list-group-item">0.6 person-hours</li>
				<ul><li class="list-group-item">Total time spent active sampling in person-hours; in this case, 2 people each spent 20 minutes surveying live bees.</li>
				</ul>
			<li class="list-group-item">0.25 person-hours</li>
				<ul><li class="list-group-item">Total time spent active sampling in person-hours; in this case, 1 person spent 15 minutes netting.</li>
				</ul>
			<li class="list-group-item">0.5 ha plot | 0.5 hours</li>
				<ul><li class="list-group-item">Recording both area sampled and duration of passive sampling time.</li>
				</ul>
				</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:samplingEffort"> https://dwc.tdwg.org/terms/#dwc:samplingEffort </a></td>
		</tr>
	</tbody>
</table>

#### Location

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_country"></a>Term Name: country</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The name of the country or major administrative unit in which the sampling location occurs.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Providing descriptive location information for an occurrence provides essential context for interpretation and supports data filtering for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. See the <a href="https://www.getty.edu/research/tools/vocabularies/tgn/"> Getty Thesaurus of Geographic Names </a> for a full controlled vocabulary list.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>United States, Canada, Mexico</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:country"> https://dwc.tdwg.org/terms/#dwc:country</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_stateProvince"></a>Term Name: stateProvince</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The name of the next smaller administrative region than the country (state, province, etc.) in which the sampling occurs.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Providing finer-grain descriptive location information for an occurrence provides essential context for interpretation and supports data filtering for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. See the <a href="https://www.getty.edu/research/tools/vocabularies/tgn/"> Getty Thesaurus of Geographic Names </a> for a full controlled vocabulary list.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Kansas, Michigan</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:stateProvince"> https://dwc.tdwg.org/terms/#dwc:stateProvince</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_decimalLatitude"></a>Term Name: decimalLatitude</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The geographic latitude (in decimal degrees, using the spatial reference system given in <b>dwc:geodeticDatum</b>) of the geographic center of a sampling location. </td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>A precise location of a wild bee occurrence provides essential context for interpretation. Providing a precise location supports species status assessments, distribution models, and other analyses relying on occurrence location.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Positive values are north of the Equator, negative values are south of it. Legal values lie between -90 and 90, inclusive. If coordinates are obtained from a phone or non-professional grade GPS then the accuracy is likely, at best, around 5 m, which would be best reflected in reporting 5 decimal places. If coordinates are derived from geographic computer software (i.e., Google Maps or GIS programs), they may have as many as six decimal places.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>-41.09837</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:decimalLatitude"> https://dwc.tdwg.org/terms/#dwc:decimalLatitude</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_decimalLongitude"></a>Term Name: decimalLongitude</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The geographic longitude (in decimal degrees, using the spatial reference system given in <b>dwc:geodeticDatum</b>) of the geographic center of a sampling location.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>A precise location of a wild bee occurrence provides essential context for interpretation. Providing a precise location supports species status assessments, distribution models, and other analyses relying on occurrence location.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Positive values are east of the Greenwich Meridian, negative values are west of it. Legal values lie between -180 and 180, inclusive. If coordinates are obtained from a phone or non-professional grade GPS then the accuracy is likely, at best, around  m, which would be best reflected in reporting 5 decimal places. If coordinates are derived from geographic computer software (i.e., Google Maps or GIS programs), they may have as many as six decimal places.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>-121.17616</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:decimalLongitude"> https://dwc.tdwg.org/terms/#dwc:decimalLongitude</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_coordinateUncertaintyInMeters"></a>Term Name: coordinateUncertaintyInMeters</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The horizontal distance (in meters) from the given <b>dwc:decimalLatitude</b> and <b>dwc:decimalLongitude</b> describing the smallest circle containing the sampling location.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>A precise location of a wild bee occurrence provides essential context for interpretation. Providing a precise location supports species status assessments, distribution models, and other analyses relying on occurrence location. Sometimes the location of an occurrence must be masked for species or other security; the extent of masking can be provided here.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>If coordinates are obtained from a GPS device, including a phone or non-professional grade GPS, the coordinate uncertainty for these devices is likely around 5 meters. Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term. This value, in most cases for current and future specimen collection, should not be greater than 10. Exceptions include if the occurrence location is masked for security reasons or if the most accurate coordinates available are less precise, as is the case for much historically-collected occurrence data.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">5 </li>
				<ul><li class="list-group-item">When precise GPS-derived coordinates with five decimal places are provided (see <b>dwc:decimalLatitude</b> and <b>dwc:decimalLongitude</b>)</li>
				</ul>
			<li class="list-group-item">0.1</li>
				<ul><li class="list-group-item">When coordinates are derived from geographic computer software (i.e., Google Maps or GIS programs) with six decimal places.</li>
				</ul>
			<li class="list-group-item">100, 1000</li>
				<ul><li class="list-group-item">When occurrence location is masked by 100 meters, if providing GPS-derived coordinates with three decimal places, or 1 km, if providing GPS-derived coordinates with two decimal places. Report any location masking, if applicable, in <b>dwc:informationWithheld</b>.</li>
				</ul>
				</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:coordinateUncertaintyInMeters"> https://dwc.tdwg.org/terms/#dwc:coordinateUncertaintyInMeters</a>, <a href="https://www.gbif.org/data-quality-requirements-occurrences#dcUncertainty"> https://www.gbif.org/data-quality-requirements-occurrences#dcUncertainty</a></td>
		</tr>
	</tbody>
</table>

#### Identification

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_identifiedBy"></a>Term Name: identifiedBy</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of names of people, groups, or organizations who identified the specimen associated with an occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing the names of the identifying personnel creates a potential point of contact for more taxonomic information regarding an occurrence.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Use full names (First [Middle Initial, if provided] Last) whenever possible. Separate the values in a list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell. This term can be used in conjunction with <b>dwc:identifiedByID</b> to connect the occurrence to the identifying personnel through platforms such as <a href="https://bionomia.net/"> Bionomia</a>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">For one identifier:</li>
				<ul><li class="list-group-item">Erika M. Tucker</li>
				</ul>
			<li class="list-group-item">For more than one identifier:</li>
				<ul><li class="list-group-item">Theodore Pappenfuss | Robert Macey</li>
				</ul>
				</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:identifiedBy"> https://dwc.tdwg.org/terms/#dwc:identifiedBy</a></td>
		</tr>
	</tbody>
</table>

#### Taxon

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_scientificName"></a>Term Name: scientificName</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The full scientific name, with authorship and date information if known.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>This term is required for publication to GBIF. Accurate identification to the lowest taxonomic rank possible creates the most useful data from a set of occurrences.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>This should be the name in lowest level taxonomic rank that can be determined. This term should not contain identification qualifications, which should instead be supplied in the <b>dwc:identificationQualifier</b> term. Authorship of the scientific name, including the date, can also be provided separately in <b>dwc:scientificNameAuthorship</b>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Hymenoptera, Halictidae, <i>Sphecodes</i> sp., <i>Osmia atriventris</i> (Cresson, 1864)</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:scientificName"> https://dwc.tdwg.org/terms/#dwc:scientificName</a>, <a href="https://www.gbif.org/data-quality-requirements-occurrences#dcSciName"> https://www.gbif.org/data-quality-requirements-occurrences#dcSciName</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_genus"></a>Term Name: genus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The full scientific name of the genus in which the occurrence is classified.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Separating the full <b>dwc:scientificName</b> into genus and specific epithet simplifies data entry and sorting for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Provide the genus of the bee with the first letter capitalized.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><i>Andrena</i>, <i>Coelioxys</i></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:genus"> https://dwc.tdwg.org/terms/#dwc:genus</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_specificEpithet"></a>Term Name: specificEpithet</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The name of the first or species epithet of the <b>dwc:scientificName</b>.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Separating the full <b>dwc:scientificName</b> into genus and specific epithet simplifies data entry and sorting for analysis.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Core</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Provide the specific epithet of the bee with the first letter lowercase. If not available, specify sp.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><i>mirabilis</i>, <i>carlini</i>, sp.</td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:specificEpithet"> https://dwc.tdwg.org/terms/#dwc:specificEpithet </a></td>
		</tr>
	</tbody>
</table>

### Recommended terms

#### Record level

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_license"></a>Term Name: license</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A document indicating the preferred terms of data use by the data provider.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Assigning a license to a dataset informs users what can be done with that dataset and the appropriate crediting procedure. Some data providers do not want their data used for commercial purposes and can specify that with their license choice.</td>
		</tr>
        	<tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>Choose a Creative Commons license that aligns with the desired potential use cases of the dataset and crediting criteria of the provider. Provide a link to the full license terms. Licenses to use include: public domain, CC-BY, CC-BY-SA, CC-BY-NC, or CC-BY-NC-SA. You may provide the name of the license holder with the optional term <b>dwc:rightsHolder</b>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
				<li class="list-group-item"><a href="https://creativecommons.org/publicdomain/zero/1.0/"> https://creativecommons.org/publicdomain/zero/1.0/</a></li>
				<li class="list-group-item"><a href="https://creativecommons.org/licenses/by/4.0/"> https://creativecommons.org/licenses/by/4.0/</a></li>
				<li class="list-group-item"><a href="https://creativecommons.org/licenses/by-sa/4.0/"> https://creativecommons.org/licenses/by-sa/4.0/</a></li>
				</ul></td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dcterms:license"> https://dwc.tdwg.org/terms/#dcterms:license</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_institutionID"></a>Term Name: institutionID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An identifier for the institution having custody of the object(s) or information referred to in the record.</td>
		</tr>
        	<tr>
			<td>Rationale</td>
			<td>Provides a location where occurrence information came from; may be used to find a point of contact for more information about an occurrence.</td>
		</tr>
       	 	<tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        	<tr>
			<td>How to use</td>
			<td>If available, use identifiers from the <a href="https://scientific-collections.gbif.org/"> Global Registry of Scientific Collections</a>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><a href="http://grscicoll.org/institution/american-museum-natural-history"> http://grscicoll.org/institution/american-museum-natural-history</a> </td>
		</tr>
        	<tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:institutionID"> https://dwc.tdwg.org/terms/#dwc:institutionID</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_collectionID"></a>Term Name: collectionID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An identifier for the collection or dataset from which the record was derived.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides more precise information regarding the location where occurrence information came from; may be used to find a point of contact for more information about an occurrence.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>If available, use identifiers from the <a href="https://scientific-collections.gbif.org/"> Global Registry of Scientific Collections</a>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><a href="http://grbio.org/cool/je3k-bvrg"> http://grbio.org/cool/je3k-bvrg</a>, <a href="http://grscicoll.org/institutional-collection/entomology "> http://grscicoll.org/institutional-collection/entomology</a> </td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:collectionID"> https://dwc.tdwg.org/terms/#dwc:collectionID</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_collectionCode"></a>Term Name: collectionCode</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The name, acronym, code, or initialism identifying the collection or dataset from which the record was derived.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides more precise information regarding the location where occurrence information came from; may be used to find a point of contact for more information about an occurrence.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide a name or acronym for the collection within the institution or dataset within a lab that houses the specimen or coordinated the observation.  If the collection is registered in the <a href="https://scientific-collections.gbif.org/"> Global Registry of Scientific Collections</a>, please use the code listed there.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>BBSL, CUIC</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:collectionCode"> https://dwc.tdwg.org/terms/#dwc:collectionCode </a></td>
		</tr>
	</tbody>
</table>

#### Occurrence

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_recordedByID"></a>Term Name: recordedByID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of the globally unique identifier(s) for the person, people, groups, or organizations responsible for recording the original occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>A unique identifier for a data collector, such as an <a href="https://orcid.org/"> ORCID iD</a>, can be used to aggregate contributions to natural history collections on platforms such as <a href="https://bionomia.net/"> Bionomia</a>.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Recommended best practice is to provide a single identifier that disambiguates the details of the collector(s) or observer(s). If a list is used, separate the values in the list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item"><a href="https://orcid.org/0000-0002-1825-0097"> https://orcid.org/0000-0002-1825-0097  </a></li>
				<ul><li class="list-group-item">for an individual collector or observer</li>
				</ul>
			<li class="list-group-item"><a href="https://orcid.org/0000-0002-1825-0097"> https://orcid.org/0000-0002-1825-0097 </a> | <a href="https://orcid.org/0000-0002-1825-0098"> https://orcid.org/0000-0002-1825-0098 </a></li>
				<ul><li class="list-group-item">for a list of collectors or observers</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:recordedByID"> https://dwc.tdwg.org/terms/#dwc:recordedByID</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_sex"></a>Term Name: sex</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The sex of the biological individual(s) represented in the occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing demographic information can improve and inform general knowledge on bee life history habits and species distribution models, particularly for at-risk species. </td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Provide the appropriate category following the controlled vocabulary list. <ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:sex</b>:</li>
				<ul><li class="list-group-item">female</li>
				<li class="list-group-item">male</li>
				<li class="list-group-item">gynandromorph</li>
				</ul>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>female, male, gynandromorph</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:sex"> https://dwc.tdwg.org/terms/#dwc:sex</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedTaxa"></a>Term Name: associatedTaxa</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of identifiers or names of taxa and the associations of this occurrence to each of them.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing the plant a bee was observed on can inform plant-pollinator networks, species conservation plans, and habitat management.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended for any active sampling conducted on bees visiting blooming flowers.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Using a key:value pair, provide the appropriate relationship from the controlled vocabulary list, using a combination of an action and a part of the plant where the bee was found. If using both the plant species and the authority key:value pairs, separate them with a comma. Enclose the entire term with curly brackets ({}, see Examples): <ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary lists for <b>dwc:associatedTaxa</b>:</li>
				<ul><li class="list-group-item">Action vocabulary: "caught on", "observed on", "visits"</li>
				<li class="list-group-item">Plant part vocabulary: "flowers of", "leaves of", "stem of"</li>
				</ul>
				</ul>
			Provide at least the genus name of the plant, though the full plant scientific name (<i>Genus species</i>) is preferred. We advise reporting the source for the taxonomic name with the authority key:value pair. 	
				</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">{"visits flowers of":"<i>Rubus</i>"}</li>
				<ul><li class="list-group-item">For reporting plant interaction only and identifying plant to genus level.</li>
				</ul>
				</ul>
				<ul class="list-group list-group-flush"> <li class="list-group-item">{"observed on flowers of":"<i>Solidago canadensis</i>",  "authority":"example authority"}</li>
				<ul><li class="list-group-item">For reporting plant interaction, full scientific name of the plant, and the source of the taxonomic identification of the plant.</li>
				<li class="list-group-item">The authority should be a full citation of the source used to identify the plant. Examples include:</li>
				<ul><li class="list-group-item">Flora Novae Angliae. 2011. Yale University Press</li>
				<li class="list-group-item"><a href="https://plants.usda.gov/home/plantProfile?symbol=SOCA6 "> https://plants.usda.gov/home/plantProfile?symbol=SOCA6 </a></li>
				<li class="list-group-item">The Jepson Manual: Vascular Plants of California. Second Edition, 2012. University of California Press</li>
				<li class="list-group-item">For further details on reporting taxonomic authority for species identifications, see <b>dwc:namePublishedIn</b>.</li>
				</ul>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:associatedTaxa"> https://dwc.tdwg.org/terms/#dwc:associatedTaxa</a></td>
		</tr>
	</tbody>
</table>

#### Material Entity

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_disposition"></a>Term Name: disposition</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The current state of a specimen with respect to the collection identified in <b>dwc:collectionCode</b> or <b>dwc:collectionID</b>.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>This term can indicate the availability of a specimen for further study.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Specify the appropriate disposition from the controlled vocabulary list. If using different terms, please define them in <b>dwc:materialEntityRemarks</b>. <ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:disposition</b>:</li>
				<ul><li class="list-group-item">inCollection: specimen is preserved in a collection.</li>
				<li class="list-group-item">missing: specimen is missing from the collection.</li>
				<li class="list-group-item">onLoan: specimen is on loan to another institution, organization, or individual.</li>
				<li class="list-group-item">destroyed: specimen has been destroyed.</li>
				</ul>
				</ul> 	
				</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">inCollection</li>
			<li class="list-group-item">destroyed</li>
			<li class="list-group-item">Awaiting processing (with details provided in <b>dwc:materialEntityRemarks</b>)</li>
			<li class="list-group-item">Missing head (with details provided in <b>dwc:materialEntityRemarks</b>)</li>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:disposition"> https://dwc.tdwg.org/terms/#dwc:disposition</a></td>
		</tr>
	</tbody>
</table>

#### Event

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_eventID"></a>Term Name: eventID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An identifier for the set of information associated with a sampling event. May be a globally unique identifier or an identifier specific to the dataset.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>When digitizing data and connecting sampling events to occurrence records, a <b>dwc:eventID</b> can be linked to a separate event table, eliminating redundancy throughout an occurrence table.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Create a unique identifier for a sampling event by combining site, date, and location information associated with that event. </td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">0320190603</li>
				<ul><li class="list-group-item">If you sampled site 3 on June 3, 2019, with 03 coming from site 3 and the remainder of the ID coming from the date formatted for <b>dwc:eventDate</b>.</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:eventID"> https://dwc.tdwg.org/terms/#dwc:eventID</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_eventRemarks"></a>Term Name: eventRemarks</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Comments or notes about the sampling event.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides additional context regarding the sampling event. This can include, but is not limited to, notes on present or historical field conditions, collector experience, or additional information on passive trap deployment.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide any additional information about the sampling event. Separate entries with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell. Field condition information can include habitat change such as mowing, fire, harvesting, etc., or pesticide application history. To report collector experience, self-identify as: Novice, Advanced Beginner, Competence, Proficient, or Expert. Additional information on passive trap deployment can include the trap colors used, trap size, height at which traps were deployed, or trap liquid type. Additional information on transects used for active sampling can indicate whether the transect was linear or meandering.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">Site planted with seeds on 2022-04-29 | collectorExperience: Advanced Beginner | meandering transect</li>
				<ul><li class="list-group-item">Describes an active sampling event at a site where seeds were planted on April 29, 2022. The collector, who has some experience, walked a meandering transect as they sampled.</li>
				</ul>
				</ul>
			<ul class="list-group list-group-flush">
			<li class="list-group-item">Blue, yellow, and white traps used | 3.25 oz cups | Dawn dish soap | site recently mowed</li>
				<ul><li class="list-group-item">Describes a passive sampling event where all three commonly used trap colors were deployed using soapy water in Solo souffle cups at a site that was recently mowed.</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:eventRemarks"> https://dwc.tdwg.org/terms/#dwc:eventRemarks</a></td>
		</tr>
	</tbody>
</table>

#### Location

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_locationID"></a>Term Name: locationID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An identifier for the set information about a sampling location. May be a globally unique identifier or an identifier specific to the dataset.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>When digitizing data and connecting sampling locations to occurrence records, a <b>dwc:locationID</b> can be linked to a separate location table, eliminating redundancy throughout an occurrence table.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Create a unique identifier for a sampling location with information associated with that location, including a site number, coordinates, or place name.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">Site09, site15, site3A</li>
				<ul><li class="list-group-item">Can be as simple as unique site names, though site numbers can also be provided in <b>dwc:fieldNumber</b>.</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:locationID "> https://dwc.tdwg.org/terms/#dwc:locationID </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_geodeticDatum"></a>Term Name: geodeticDatum</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The ellipsoid, geodetic datum, or spatial reference system upon which the geographic coordinates given in <b>dwc:decimalLatitude</b> and <b>dwc:decimalLongitude</b> are based.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing a datum gives context to provided coordinates. GBIF assumes the datum is WGS84. If you don't know what coordinate system you are using it is most likely WGS84, which is the default for publicly available maps like Google Maps and is what is used for Global Positioning Systems (GPS). If coordinates were provided from a different datum, that should be specified. For instance, NAD27 was once a common datum, but coordinates in NAD27 can be up to 200 meters away from those in WGS84.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>The best practice is to use the <a href="https://epsg.io/">EPSG code</a> for the datum or spatial reference system. The EPSG code for WGS84 is <a href="https://epsg.io/4326">EPSG:4326</a>. If an EPSG code is not available, the name of the datum or spatial reference system may be provided.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>EPSG:4326, EPSG:4269, WGS84, NAD27, NAD83</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:geodeticDatum"> https://dwc.tdwg.org/terms/#dwc:geodeticDatum</a>, <a href="https://www.gbif.org/data-quality-requirements-occurrences#dcGeodeticDatum"> https://www.gbif.org/data-quality-requirements-occurrences#dcGeodeticDatum</a></td>
		</tr>
	</tbody>
</table>

#### Identification

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_verbatimIdentification"></a>Term Name: verbatimIdentification</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A string representing the taxonomic identification as it appeared in the original record. This term is meant to be used in addition to <b>dwc:scientificName</b>, not instead of it.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>This term can be used to translate original label text on historic specimens, to store the original identification if the <b>dwc:scientificName</b> changes, or in any other case where the original identification is different from the current identification.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Translate label text verbatim when digitizing.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><i>Osmia besseyae</i> Cockerell TYPE (<a href="https://library.big-bee.net/portal/collections/individual/index.php?occid=1667260"> https://library.big-bee.net/portal/collections/individual/index.php?occid=1667260</a>)</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:verbatimIdentification "> https://dwc.tdwg.org/terms/#dwc:verbatimIdentification </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_identificationQualifier"></a>Term Name: identificationQualifier</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A brief phrase or a standard term ("cf.", "aff.") to express the determiner's doubts about the identification.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>This term can provide more context about the taxonomy of an occurrence.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended, if applicable. Must be used with <b>dwc:taxonRank</b>.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Provide the appropriate qualifier, if applicable. <ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:identificationQualifier</b> (definitions taken from <a href="https://doi.org/10.1111/2041-210X.12594"> Sigovini et al., 2016</a>)</li>
				<ul><li class="list-group-item">Affinis (aff.): affinity with a known species; has affinity with</li>
				<li class="list-group-item">Confer (cf.): to compare or be compared with</li>
				<li class="list-group-item">Species incerta (?, sp. inc, or inc.): uncertain species</li>
				<li class="list-group-item">Species proxima (prox.): the nearest species</li>
				<li class="list-group-item">Species near (nr.): near but not identical to a species</li>
				<li class="list-group-item">Stetit (stet.): further identification has not been attempted</li>
				</ul>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">cf. <i>vincta</i></li>
				<ul><li class="list-group-item">for <i>Nomada</i> cf. <i>vincta</i> with accompanying values <i>Nomada</i> in <b>dwc:genus</b>, <i>vincta</i> in <b>dwc:specificEpithet</b>, and cf. species in <b>dwc:taxonRank</b>.</li></ul>
				</ul>
				<ul class="list-group list-group-flush">
			<li class="list-group-item">aff. <i>modestus</i> </li>
				<ul><li class="list-group-item">for <i>Hylaeus</i> aff. <i>modestus</i> with accompanying values <i>Hylaeus</i> in <b>dwc:genus</b>, <i>modestus</i> in <b>dwc:specificEpithet</b>, and aff. species in <b>dwc:taxonRank</b>.</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:identificationQualifier"> https://dwc.tdwg.org/terms/#dwc:identificationQualifier</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_identifiedByID"></a>Term Name: identifiedByID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of the globally unique identifier(s) for the person, people, groups, or organizations responsible for identifying the original occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>A unique identifier for for bee identifying personnel, such as an <a href="https://orcid.org/"> ORCID iD</a>, can be used to aggregate contributions to natural history collections on platforms such as <a href="https://bionomia.net/"> Bionomia</a>.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Recommended best practice is to provide a single identifier that disambiguates the details of the identifying agent. If a list is used, separate the values in the list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item"><a href="https://orcid.org/0000-0002-1825-0097"> https://orcid.org/0000-0002-1825-0097  </a></li>
				<ul><li class="list-group-item">for an individual identifier</li>
				</ul>
			<li class="list-group-item"><a href="https://orcid.org/0000-0002-1825-0097"> https://orcid.org/0000-0002-1825-0097 </a> | <a href="https://orcid.org/0000-0002-1825-0098"> https://orcid.org/0000-0002-1825-0098 </a></li>
				<ul><li class="list-group-item">for a list of identifiers</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:identifiedByID"> https://dwc.tdwg.org/terms/#dwc:identifiedByID</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_dateIdentified"></a>Term Name: dateIdentified</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The date a specimen associated with an occurrence was identified.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides context for the taxonomic identification.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the date the taxonomic identification was determined, using a date that conforms to ISO 8601-1:2019.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>2020-08-09, 1987-04, 1963</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:dateIdentified"> https://dwc.tdwg.org/terms/#dwc:dateIdentified </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_identificationReferences"></a>Term Name: identificationReferences</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of references used to identify a specimen. </td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides context and improves reproducibility for the taxonomic identification.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide citations for references used to identify specimens, separating the values in a list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Portman ZM, Arduser M, Lane IG, Cariveau DP (2022) A review of the <i>Augochloropsis</i> (Hymenoptera, Halictidae) and keys to the shiny green Halictinae of the midwestern United States. ZooKeys 1130: 103–152. <a href="https://doi.org/10.3897/zookeys.1130.86413"> https://doi.org/10.3897/zookeys.1130.86413 </a> | <a href="https://www.discoverlife.org/mp/20q?guide=Bee_genera"> discoverlife.org</a></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:identificationReferences"> https://dwc.tdwg.org/terms/#dwc:identificationReferences</a></td>
		</tr>
	</tbody>
</table>

#### Taxon

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_taxonID"></a>Term Name: taxonID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An identifier for the information describing the taxonomy of an occurrence. May be a globally unique identifier or an identifier specific to the dataset.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>When digitizing data and connecting species identifications to occurrence records in a relational database or an Excel workbook, a <b>dwc:taxonID</b> can be linked to a separate taxon table, streamlining an occurrence table.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>There are multiple sources for <b>dwc:taxonID</b>s for bees; these include species pages on GBIF or DiscoverLife and ITIS taxonomic serial numbers. Any or all of these identifiers can be provided in <b>dwc:taxonID</b>. Separate multiple identifiers in a list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><a href="https://www.gbif.org/species/5042859"> https://www.gbif.org/species/5042859</a> | Taxonomic Serial No.: 757559 | <a href="https://www.discoverlife.org/20/q?search=Agapostemon+texanus"> https://www.discoverlife.org/20/q?search=Agapostemon+texanus</a></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:taxonID"> https://dwc.tdwg.org/terms/#dwc:taxonID </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_nameAccordingTo"></a>Term Name: nameAccordingTo</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The reference to the source in which the specific taxon concept circumscription is defined or implied, traditionally signified by the Latin "sensu" or "sec." (from secundum, meaning "according to").</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing taxonomic reference information allows occurrence identifications to be verified or examined in further study.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>For taxa that result from identifications, a reference to the keys, monographs, experts and other sources should be given.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Ascher, J. S. and J. Pickering. 2024. Discover Life bee species guide and world checklist (Hymenoptera: Apoidea: Anthophila). <a href="http://www.discoverlife.org/mp/20q?guide=Apoidea_species"> http://www.discoverlife.org/mp/20q?guide=Apoidea_species</a></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:nameAccordingTo"> https://dwc.tdwg.org/terms/#dwc:nameAccordingTo</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_family"></a>Term Name: family</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The full scientific name of the family in which the occurrence is classified.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context and supports data filtering for analysis.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the family name.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Halictidae, Colletidae</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:family"> https://dwc.tdwg.org/terms/#dwc:family </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_infraspecificEpithet"></a>Term Name: infraspecificEpithet</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The name of the lowest or terminal infraspecific epithet of the <b>dwc:scientificName</b>, excluding any rank designation.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context. Accurate identification to the lowest taxonomic rank possible creates the most useful data from a set of occurrences.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the subspecies name.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item"><i>virginica</i></li>
				<ul><li class="list-group-item">for <i>Xylocopoides virginica virginica</i></li>
				</ul>
			<li class="list-group-item"><i>propinqua</i></li>
				<ul><li class="list-group-item">for <i>Osmia lignaria propinqua</i></li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:infraspecificEpithet"> https://dwc.tdwg.org/terms/#dwc:infraspecificEpithet </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_scientificNameAuthorship"></a>Term Name: scientificNameAuthorship</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The authorship information for the <b>dwc:scientificName</b>.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Recommended</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the authorship and date of the scientific name.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Cockerell, 1906</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:scientificNameAuthorship"> https://dwc.tdwg.org/terms/#dwc:scientificNameAuthorship</a></td>
		</tr>
	</tbody>
</table>

### Optional terms

#### Record level

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_rightsHolder"></a>Term Name: rightsHolder</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A person or organization owning or managing rights over the resource.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides contact information regarding use of shared data and license choice.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td> Provide the name(s) of the person, organization, or institution responsible for the rights of a shared dataset. Separate multiple values with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>The Regents of the University of California</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dcterms:rightsHolder"> https://dwc.tdwg.org/terms/#dcterms:rightsHolder</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_dynamicProperties"></a>Term Name: dynamicProperties</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of additional measurements, facts, characteristics, or assertions about the record. This term is meant to provide a mechanism for structured content.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Reporting site conditions during sampling events can provide important context for interpretation, including informing occupancy models. Darwin Core does not currently have terms for these conditions; therefore, <i>The Wild Bee Data Standard</i> uses <b>dwc:dynamicProperties</b> to report them.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Report any or all of the following site conditions using key:value pairs. Note that numeric values do not need quotation marks. If providing multiple key:value pairs, separate them with commas. Enclose the entire term in curly brackets ({}, see Example). 	<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:dynamicProperties</b>:</li>
				<ul><li class="list-group-item">airTemperature: report degrees Celsius</li>
				<li class="list-group-item">relHumidity: report relative humidity percent value</li>
				<li class="list-group-item">windSpeed: report wind speed and unit measure</li>
				<li class="list-group-item">cloudCover: report one of the following: clear, partly cloudy, mostly cloudy, light overcast, dark overcast</li>
				<li class="list-group-item">precip: report one of the following: none, light rain</li>
				<ul><li class="list-group-item">Note that light rain is only allowed for long term passive traps, such as cup or vane traps. Nearly all wild bee sampling should be conducted with no precipitation.</li></ul>
				<li class="list-group-item">AQI: air quality index as reported for the sampling area</li>
				</ul>
				</ul></td>
		</tr>
		<tr>
			<td>Example</td>
			<td>{"relHumidity":28, "airTemperature":22, "windSpeed":"3 kph", "cloudCover":"light overcast", "precip":"none", "AQI":34}</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:dynamicProperties"> https://dwc.tdwg.org/terms/#dwc:dynamicProperties</a></td>
		</tr>
	</tbody>
</table>

#### Occurrence

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_lifeStage"></a>Term Name: lifeStage</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The age class or life stage of the organism(s) at the time the occurrence was recorded.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing demographic information can improve and inform general knowledge on bee life history habits and species distribution models, particularly for at-risk species.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional, but required if the specimen is not an adult.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Provide the appropriate category following the controlled vocabulary list.	<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:lifeStage</b>:</li>
				<ul><li class="list-group-item">egg</li>
				<li class="list-group-item">larva</li>
				<li class="list-group-item">pupa</li>
				<li class="list-group-item">adult</li>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>larva, adult</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the occupancy of focal species protocol (Otto et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:lifeStage"> https://dwc.tdwg.org/terms/#dwc:lifeStage </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_caste"></a>Term Name: caste</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Categorization of individuals for eusocial species.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing demographic information can improve and inform general knowledge on bee life history habits and species distribution models, particularly for at-risk species.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Provide the appropriate category following the controlled vocabulary list.	<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:caste</b>:</li>
				<ul><li class="list-group-item">queen</li>
				<li class="list-group-item">worker</li>
				<li class="list-group-item">drone</li>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>queen, worker</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the occupancy of focal species protocol (Otto et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:caste"> https://dwc.tdwg.org/terms/#dwc:caste</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_behavior"></a>Term Name: behavior</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The behavior shown by the subject at the time the occurrence was recorded.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing demographic information can improve and inform general knowledge on bee life history habits and species distribution models, particularly for at-risk species.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Provide the appropriate category following the controlled vocabulary list.	<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:behavior</b>:</li>
				<ul><li class="list-group-item">foraging</li>
				<li class="list-group-item">collecting pollen</li>
				<li class="list-group-item">collecting nectar</li>
				<li class="list-group-item">nesting</li>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Collecting pollen, Nesting</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the occupancy of focal species protocol (Otto et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:behavior"> https://dwc.tdwg.org/terms/#dwc:behavior </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_vitality"></a>Term Name: vitality</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An indication of whether an organism was alive or dead at the time of collection or observation.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing demographic information can improve and inform general knowledge on bee life history habits and species distribution models, particularly for at-risk species.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. Provide the appropriate category following the controlled vocabulary list.	<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:vitality</b>:</li>
				<ul><li class="list-group-item">alive</li>
				<li class="list-group-item">dead</li>
				<li class="list-group-item">moribund</li>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>alive, dead</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the occupancy of focal species protocol (Otto et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:vitality"> https://dwc.tdwg.org/terms/#dwc:vitality </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedMedia"></a>Term Name: associatedMedia</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of identifiers of media associated with the occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides links to accompanying photos related to the occurrence, including but not limited to site photos, plant photos, trap photos, or specimen photos. May instead provide a host institution housing non-public image data or other media.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Media shared publicly via <b>dwc:associatedMedia</b> must have an associated identifier, whether that is a website, a publication, or a UUID. Please provide any relevant identifiers, separated by a vertical bar if necessary. For non-publicly held media, please provide the name of the institution that manages the media data.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item"><a href=" https://www.flickr.com/photos/usgsbiml/52264266775/"> https://www.flickr.com/photos/usgsbiml/52264266775/</a></li>
			</ul>
			<ul class="list-group list-group-flush">
			<li class="list-group-item">University of Minnesota</li>
				<ul><li class="list-group-item">Provides the home institution for non-publicly held media.</li>
				</ul>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:associatedMedia"> https://dwc.tdwg.org/terms/#dwc:associatedMedia</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedOccurrences"></a>Term Name: associatedOccurrences</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of identifiers of other occurrence records and their associations to this occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Links to other bee or plant occurrences that were observed, detected, or collected around a bee occurrence. This differs from <b>dwc:associatedTaxa</b> in that a plant listed here can be another plant in the vicinity of the plant the occurrence was directly interacting with. However, this term can also be used to link to the occurrence of the plant described in <b>dwc:associatedTaxa</b>. Use of this term may provide more context for focal species analyses.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Use a key:value pair, with the key describing the relationship with the associated occurrence and the value being the unique ID for that occurrence. The unique ID will ideally be a URL link to the occurrence provided on a data portal. We do not provide a controlled vocabulary for the possible relationships; be concise but descriptive when generating these keys. The unique ID can describe for another bee or plant occurrence that a bee occurrence was observed, detected, or collected on. It could also describe the occurrence itself with the use of the “same as” or “same occurrence as” key. If providing multiple key:value pairs, separate them with a comma. Enclose the entire term in curly brackets ({}, see Examples).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">{“parasitized by”:<a href="https://www.gbif.org/occurrence/2851169659"> https://www.gbif.org/occurrence/2851169659</a>}</li>
			<ul><li class="list-group-item">Describes an associated occurrence of a parasitic bee.</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush">
			<li class="list-group-item">{“observed near”:<a href=" https://www.inaturalist.org/observations/216532139"> https://www.inaturalist.org/observations/216532139</a>} </li>
				<ul><li class="list-group-item">Describes an associated occurrence of the plant a bee was observed on.</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush">
			<li class="list-group-item">{“same as”:<a href="https://www.inaturalist.org/observations/220375291"> https://www.inaturalist.org/observations/220375291</a>} or {“same occurrence as”:<a href="https://www.inaturalist.org/observations/220375291"> https://www.inaturalist.org/observations/220375291</a>}</li>
				<ul><li class="list-group-item">Describes the bee occurrence as posted on iNaturalist. This example can also be used for plant occurrences described in dwc:associatedTaxa.</li>
				</ul>
			</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:associatedOccurrences"> https://dwc.tdwg.org/terms/#dwc:associatedOccurrences</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_occurrenceRemarks"></a>Term Name: occurrenceRemarks</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Comments or notes about the occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>This term provides additional context for the corresponding occurrence. Here, the term is used to describe how a bee was captured.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide a brief description of how and where the bee was captured or observed.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>netted in air, netted on the ground</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the communities protocol (Levenson et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:occurrenceRemarks"> https://dwc.tdwg.org/terms/#dwc:occurrenceRemarks</a></td>
		</tr>
	</tbody>
</table>

#### Material Entity

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_preparations"></a>Term Name: preparations</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of preparations and preservation methods for material associated with an occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Describes procedures taken to preserve material from a physical specimen for molecular or tissue analyses. Can also be used to reference whole specimen preparation.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Core for molecular (López-Uribe et al., 2024) and parasite and pathogen (Strange et al., 2024) protocols, optional otherwise.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Indicate what, if any, material was extracted from the specimen and what that material will be used for. For whole specimens, indicate their final preservation method.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>DNA extract, -80 freezer, pinned, in alcohol</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All,, particularly the molecular (López-Uribe et al., 2024) and parasite and pathogen (Strange et al., 2024) protocols.</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:preparations"> https://dwc.tdwg.org/terms/#dwc:preparations</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedSequences"></a>Term Name: associatedSequences</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of identifiers of genetic sequence information associated with an occurrence.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Links to genetic sequence data for a specimen.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide one or multiple means to locate genetic sequence information. Identifiers can include publications, globally unique identifiers, and URLs. Separate identifiers in a list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><a href="https://www.boldsystems.org/index.php/Public_RecordView?processid=BEECC462-08"> https://www.boldsystems.org/index.php/Public_RecordView?processid=BEECC462-08</a>, <a href="https://www.boldsystems.org/index.php/Public_RecordView?processid=BUSA207-05"> https://www.boldsystems.org/index.php/Public_RecordView?processid=BUSA207-05</a></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the molecular protocol (López-Uribe et al., 2024).</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:associatedSequences"> https://dwc.tdwg.org/terms/#dwc:associatedSequences </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_materialEntityRemarks"></a>Term Name: materialEntityRemarks</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Comments or notes about a MaterialEntity.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>This term provides context for other terms used in the MaterialEntity category. In <i>The Wild Bee Data Standard</i>, these terms are <b>dwc:disposition</b>, <b>dwc:preparations</b>, and <b>dwc:associatedSequences</b>.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Core for molecular (López-Uribe et al., 2024) and parasite and pathogen (Strange et al., 2024) protocols, optional otherwise.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Use this term to provide information related to <b>dwc:disposition</b> that is not included in the controlled vocabulary list. This term is also used in the Bee Monitoring RCN protocols to provide more context for any material taken for molecular or tissue analyses for which the final storage conditions are described in <b>dwc:preparations</b>.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush"><li class="list-group-item">in lab </li>
			<ul><li class="list-group-item">Example related to <b>dwc:disposition</b> that indicates the specimen is in the laboratory awaiting full processing.</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush"><li class="list-group-item">sterilized with 10% bleach | stored on ice between collection and final storage | 0.8 hour between collection and final storage | stored in Sample Lab, Sample Location</li>
				<ul><li class="list-group-item">Example specific to Bee Monitoring RCN protocols for molecular and tissue data analysis.</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush"><li class="list-group-item">Head is missing from specimen</li>
				<ul><li class="list-group-item">Example related to <b>dwc:disposition</b> that provides a note about specimen condition.</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush"><li class="list-group-item">Leg removed for molecular analysis</li>
				<ul><li class="list-group-item">Example related to <b>dwc:disposition</b> that provides a note about specimen condition.</li>
				</ul>
			</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, particularly the molecular (López-Uribe et al., 2024) and parasite and pathogen (Strange et al., 2024) protocols.</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:materialEntityRemarks"> https://dwc.tdwg.org/terms/#dwc:materialEntityRemarks</a></td>
		</tr>
	</tbody>
</table>

#### Event

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_fieldNumber"></a>Term Name: fieldNumber</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>An identifier for a sampling event in the field that links field-based or collected information to an occurrence. Examples include a site number or a vial number associated with a bee or group of bees collected at a site. Note that it is possible for multiple vials to be collected at a site during a sampling event. Using this term to indicate site number, vial number, or some other field-based identifier is allowable.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Clarifies sampling protocol and provides context for interpretation.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide any site-identifying information here.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush"><li class="list-group-item">Site numbers: Site 1, 5A-2015, Farm Site 6</li>
			<li class="list-group-item">Vial numbers: 2, AM-Site4-08</li>
				</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:fieldNumber"> https://dwc.tdwg.org/terms/#dwc:fieldNumber </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_habitat"></a>Term Name: habitat</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A category or description of the habitat in which the sampling event occurred.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Habitat type has ecological implications on bee community assemblage.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide any description of the habitat type where the specimen was observed or collected. For a common reference, provide a habitat type and number from either the NRCS Ecological Site Descriptions (ESD) or the EPA Level 3 Ecoregions, specifying which source was used using a key:value pair. If using a key:value pair, enclose the entire term in curly brackets ({}, see Examples). <ul class="list-group list-group-flush"><li class="list-group-item">More on NRCS ESDs: <a href="https://www.nrcs.usda.gov/getting-assistance/technical-assistance/ecological-sciences/ecological-site-descriptions"> https://www.nrcs.usda.gov/getting-assistance/technical-assistance/ecological-sciences/ecological-site-descriptions</a></li>
			<li class="list-group-item">More on EPA Ecoregions: <a href="https://www.epa.gov/eco-research/level-iii-and-iv-ecoregions-continental-united-states"> https://www.epa.gov/eco-research/level-iii-and-iv-ecoregions-continental-united-states</a></li>
				</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>oak savanna, steppe, {“EPA Level 3 Ecoregion”:“Ozark Highlands (39)”}, {“NRCS ESD”:“Snake River Plains (011X)”}</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:habitat"> https://dwc.tdwg.org/terms/#dwc:habitat</a></td>
		</tr>
	</tbody>
</table>

#### Location

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_county"></a>Term Name: county</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The full, unabbreviated name of the next smaller administrative region than <b>dwc:stateProvince</b> (county, department, etc.) in which the sampling location occurs. </td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing finer-grain descriptive location information for an occurrence provides essential context for interpretation and supports data filtering for analysis.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>This term uses a controlled vocabulary. See the <a href="https://www.getty.edu/research/tools/vocabularies/tgn/"> Getty Thesaurus of Geographic Names </a> for a full controlled vocabulary list.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Ness, Menominee</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:county"> https://dwc.tdwg.org/terms/#dwc:county </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_locality"></a>Term Name: locality</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The specific description of the place.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Descriptive localities can provide important context for interpreting occurrence information.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>A locality can provide any useful collection location name such as: town, park, study site code name, street address, or an amalgamation of other location names in your dataset.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Grand Staircase-Escalante National Monument, 500 m from Hwy 1 at Old Orchard Rd</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:locality"> https://dwc.tdwg.org/terms/#dwc:locality </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_verbatimElevation"></a>Term Name: verbatimElevation</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The original description of the elevation (altitude, usually above sea level) of the sampling location.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Elevation has ecological implications on bee community assemblage.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide an estimate of elevation above sea level in meters. The value can be gathered in the field with GPS or via spatial software tools.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>150 m</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:verbatimElevation"> https://dwc.tdwg.org/terms/#dwc:verbatimElevation </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_coordinatePrecision"></a>Term Name: coordinatePrecision</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A decimal representation of the precision of the coordinates given in dwc:decimalLatitude and dwc:decimalLongitude.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing precision is another way of stating uncertainty in the coordinates in conjunction with the core term <b>dwc:coordinateUncertaintyInMeters</b>. It can also clarify rounding errors that may occur in computer software when the end of a coordinate value is zero. A precise location of a wild bee occurrence provides essential context for interpretation. Providing a precise location supports species status assessments, distribution models, and other analyses relying on occurrence location. Sometimes the location of an occurrence must be masked for species or other security; the extent of masking can be provided here.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the appropriate number of decimals in the coordinates of the occurrence record.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush"><li class="list-group-item">0.00001</li>
			<ul><li class="list-group-item">precise to 5 m; best practice for <i>The Wild Bee Data Standard</i>. Associated with GPS-derived coordinates with five decimal places.</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush"><li class="list-group-item">0.000001</li>
				<ul><li class="list-group-item">precise to 0.11 m; associated with coordinates with six decimal places derived from geographic computer software (i.e., Google Maps, GIS programs).</li>
				</ul>
			</ul>
			<ul class="list-group list-group-flush"><li class="list-group-item">0.01 </li>
				<ul><li class="list-group-item">precise to 1 km. The value for <b>dwc:coordinateUncertaintyInMeters</b> will be 1000, and the number of decimal places in <b>dwc:decimalLatitude</b> and <b>dwc:decimalLongitude</b> will be 1. Be sure to indicate location masking in <b>dwc:informationWithheld</b>.</li>
				</ul>
			</ul>
			</ul></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:coordinatePrecision"> https://dwc.tdwg.org/terms/#dwc:coordinatePrecision </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_georeferencedBy"></a>Term Name: georeferencedBy</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of names of people, groups, or organizations who determined the georeference (spatial representation) for the sampling location.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Providing the names of the georeferencing personnel creates a potential point of contact for more information regarding an occurrence or its collecting event.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Use full names (First [Middle Initial, if provided] Last) whenever possible. Separate the values in a list with space vertical bar space ( | ); this separator is used throughout the Darwin Core standard to concatenate multiple entries in a cell.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Amelia Earhart | Harry Manning </td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:georeferencedBy"> https://dwc.tdwg.org/terms/#dwc:georeferencedBy </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_ georeferenceRemarks"></a>Term Name:  georeferenceRemarks</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Notes or comments about the spatial description determination.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Some organizations require detailed information regarding the georeference process, including how many satellites triangulated the coordinates or the type of device used to determine the coordinates.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide any relevant information to satisfy organization requirements, including the number of satellites or the device type used to record coordinates. To clarify to users outside your organization what information is being provided, describe the information using a key:value pair. Note that numerical values do not need quotation marks. If using multiple key:value pairs, separate them with a comma. Enclose the entire term in curly brackets ({}, see Example).</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>{“number of satellites”:5, “device type used to record coordinates”: “Garmin eTrex 22x”}</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:georeferenceRemarks"> https://dwc.tdwg.org/terms/#dwc:georeferenceRemarks</a></td>
		</tr>
	</tbody>
</table>

#### Identification

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_ typeStatus"></a>Term Name: typeStatus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A list of nomenclatural types (type status, typified scientific name, publication) applied to the subject.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context by allowing for identification verification.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional if not a type specimen, but required if the occurrence record refers to a type specimen.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide any type status information, if applicable.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>holotype of <i>Halictus confusus</i></td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:typeStatus"> https://dwc.tdwg.org/terms/#dwc:typeStatus</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_ identificationRemarks"></a>Term Name: identificationRemarks</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>Any comments or notes regarding the identification of a specimen.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context and improves reproducibility for taxonomic identification.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide any ancillary information that may be helpful to others attempting to verify, modify, or study the identification of a specimen.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Made determination based on malar space.</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:identificationRemarks"> https://dwc.tdwg.org/terms/#dwc:identificationRemarks</a></td>
		</tr>
	</tbody>
</table>

#### Taxon

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_namePublishedIn"></a>Term Name: namePublishedIn</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A reference for the publication in which the dwc:scientificName was originally established.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context and improves reproducibility for taxonomic identification by allowing for reference verification by data users.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide a full citation for a taxonomic reference.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Sandhouse GA. (1937) The bees of the genera Augochlora, Augochloropsis, and Augochlorella (Hymenoptera; Apoidea) occurring in the United States. Journal of the Washington Academy of Sciences 27: 65–79.</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:namePublishedIn"> https://dwc.tdwg.org/terms/#dwc:namePublishedIn</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_tribe"></a>Term Name: tribe</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The full scientific name of the tribe in which the occurrence is classified.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context. Accurate identification to the lowest taxonomic rank possible creates the most useful data from a set of occurrences.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the tribe name.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Colletini, Perditini, Nomiini</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:tribe">  https://dwc.tdwg.org/terms/#dwc:tribe</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_subgenus"></a>Term Name: subgenus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The full scientific name of the subgenus in which the occurrence is classified. Values should include the genus to avoid homonym confusion.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context. Accurate identification to the lowest taxonomic rank possible creates the most useful data from a set of occurrences.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the subgenus name in parentheses after the genus name.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><i>Bombus</i> (<i>Cullumanobombus</i>), <i>Andrena</i> (<i>Melandrena</i>), <i>Lasioglossum</i> (<i>Dialictus</i>)</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:subgenus">  https://dwc.tdwg.org/terms/#dwc:subgenus</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_taxonRank"></a>Term Name: taxonRank</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>The taxonomic rank of the most specific name in the <b>dwc:scientificName</b>.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Provides important taxonomic context. Accurate identification to the lowest taxonomic rank possible creates the most useful data from a set of occurrences.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional, but required if <b>dwc:identificationQualifier</b> is used.</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide the finest resolution of the occurrence species identification.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>genus, species, subspecies</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:taxonRank">  https://dwc.tdwg.org/terms/#dwc:taxonRank </a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_vernacularName"></a>Term Name: vernacularName</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Definition</td>
			<td>A common or vernacular name.</td>
		</tr>
        <tr>
			<td>Rationale</td>
			<td>Some data collectors, managers, or users may be more familiar with a common name for a species and prefer to use that.</td>
		</tr>
        <tr>
			<td>Requirement</td>
			<td>Optional</td>
		</tr>
        <tr>
			<td>How to use</td>
			<td>Provide a common name.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>Two-spotted bumble bee</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All</td>
		</tr>
		<tr>
			<td>For more detail</td>
			<td><a href="https://dwc.tdwg.org/terms/#dwc:vernacularName"> https://dwc.tdwg.org/terms/#dwc:vernacularName</a></td>
		</tr>
	</tbody>
</table>



# The Wild Bee Data Standard List of Core Terms

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

## Term List Details

### Core terms

#### Record level

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
            <li class="list-group-item"><code>USDA-ARS</code></li>
            <li class="list-group-item"><code>UNHC</code></li>
            <li class="list-group-item">iNaturalist</li>
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
			<td>This term is required for publication to GBIF and describes the type of occurrence record, which is essential context for interpretation.</td>
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
				<li class="list-group-item">HumanObservation, to describe wild bees or plants observed in the field and captured in photographs taken in person when using non-lethal sampling methods.</li>
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
			<td>An unique identifier for the occurrence.</td>
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
			<td>An unique identifier within a dataset or collection.</td>
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
			<li class="list-group-item">Most records will have an entry of 1 for <b>dwc:individualCount</b>, as most records correspond to an observation or collection (a detection) of a single organism.</li>
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
			<td>All, but particularly important for the focal species protocol (Otto et al., 2024).</td>
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
			<td>This term uses a controlled vocabulary. Although the Darwin Core standard recommends the use of “present” and “absent” to designate occurrence status, we suggest observers instead use “detected” and “not detected” when recording results from sampling events.  Absence is seldom known with certainty and we recommend avoiding the use of this term during data collection.
			<ul class="list-group list-group-flush">
			<li class="list-group-item">Controlled vocabulary list for <b>dwc:occurrenceStatus</b>:</li>
				<ul><li class="list-group-item">Detected</li>
				<li class="list-group-item">Not detected</li>
				</ul>
			</ul></td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Detected, Not detected</td>
		</tr>
        <tr>
			<td>Relevant protocols</td>
			<td>All, but particularly important for the focal species protocol (Otto et al., 2024).</td>
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
				<ul><li class="list-group-item">For sampling over a maximum 24 hour period that spans two dates. This is interpreted as: collections started on August 14, 2015 at 4pm local time and ended August 15, 2015 at 4pm local time. Note that in this case, <b>dwc:eventTime</b> does not need to be provided, but can be, as the sampling time interval is included in <b>dwc:eventDate</b>.</li>
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
			<td>This is a numeric field. Enter the four digit year the sampling event occurred.</td>
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
			<td>This is a numeric field. Enter the one or two digit month when the sampling event occurred. Bee communities vary widely by month.</td>
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
			<td>This is a numeric field. Enter the one or two digit day of the month when the sampling event occurred. If sampling occurred over multiple days; i.e., passive traps were used, do not use this term, as it only records one day. The terms <b>dwc:year</b> and <b>dwc:month</b> should still be used if sampling occurred over multiple days.</td>
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
			<td>Positive values are north of the Equator, negative values are south of it. Legal values lie between -90 and 90, inclusive. If coordinates are obtained from a phone or non-professional grade GPS then the accuracy is likely, at best, around 10 m, which would be best reflected in reporting 4 decimal places. If coordinates are derived from geographic computer software (i.e., Google Maps or GIS programs), they may have as many as six decimal places.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>-41.0983</td>
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
			<td>Positive values are east of the Greenwich Meridian, negative values are west of it. Legal values lie between -180 and 180, inclusive. If coordinates are obtained from a phone or non-professional grade GPS then the accuracy is likely, at best, around 10 m, which would be best reflected in reporting 4 decimal places. If coordinates are derived from geographic computer software (i.e., Google Maps or GIS programs), they may have as many as six decimal places.</td>
		</tr>
		<tr>
			<td>Example</td>
			<td>-121.1761</td>
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
			<td>If coordinates are obtained from a GPS device, including a phone or non-professional grade GPS, the coordinate uncertainty for these devices is likely around 10 meters. Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term. This value, in most cases for current and future specimen collection, should not be greater than 10. Exceptions include if the occurrence location is masked for security reasons or if the most accurate coordinates available are less precise, as is the case for many historically-collected specimens.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
			<li class="list-group-item">10 </li>
				<ul><li class="list-group-item">When precise GPS-derived coordinates with four decimal places are provided (see <b>dwc:decimalLatitude</b> and <b>dwc:decimalLongitude</b>)</li>
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

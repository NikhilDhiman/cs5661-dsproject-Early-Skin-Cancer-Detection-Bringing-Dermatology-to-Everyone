# ISIC 2024 - Skin Cancer Detection with 3D-TBP
The SLICE-3D dataset is a large-scale, real-world collection of standardized skin lesion images used for skin cancer detection. It features JPEG image crops (15x15 mm field of view) extracted from 3D Total Body Photography (TBP) using the Vectra WB360 system by Canfield Scientific. These images represent the complete cutaneous surface of patients from diverse populations across nine institutions on three continents, spanning from 2015 to 2024.

Each image corresponds to a lesion identified by AI-based software and is linked to metadata provided in a CSV file, which includes a binary diagnostic label (target: malignant = 1, benign = 0), patient demographics (e.g., age, sex), lesion site, image source, and diagnosis type. Labels are either strong (histopathologically confirmed) or weak (clinical assessment only).

This dataset is designed for binary classification tasks-predicting the probability that a given lesion is malignant. It is valuable for training machine learning models in dermatological diagnostics, particularly in non-dermoscopic contexts. The dataset supports the development of scalable skin cancer screening tools and aims to improve early detection by mimicking real-world imaging scenarios, making it suitable for both clinical research and AI-driven healthcare applications.

#### Dataset Link
<!-- info: Provide a link to the dataset: -->
<!-- width: half -->
[Dataset Link](https://www.kaggle.com/competitions/isic-2024-challenge/data)

## Authorship
### Publishers
#### Publishing Organization(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the institution or organization responsible
for publishing the dataset: -->
Scientific Data
International Skin Imaging Collaboration (ISIC)


#### Industry Type(s)
<!-- scope: periscope -->
<!-- info: Select **all applicable** industry types to which the publishing
organizations belong: -->
- Academic - Tech
- Not-for-profit - Tech

#### Contact Detail(s)
<!-- scope: microscope -->
<!-- info: Provide publisher contact details: -->
- **Publishing POC:** Dr. Clara Alvarado, ISIC Consortium
- **Affiliation:** ISIC Research Foundation
Memorial Sloan Kettering Cancer Center (USA)
Hospital Clinic de Barcelona (Spain)
The University of Queensland (Australia)
Medical University of Vienna (Austria)
University of Athens (Greece)
Melanoma Institute Australia (Australia)
University Hospital of Basel (Switzerland)
Alfred Hospital (Australia)
FNQH Cairns (Australia)

- **Contact:** contact@isic.org
- **Mailing List:** Provide a mailing list if available
- **Website:** https://www.isic-archive.com

### Dataset Owners
#### Team(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the groups or team(s) that own the dataset: -->
Name of Group or Team
International Skin Imaging Collaboration. SLICE-3D 2024 Challenge Dataset. International Skin Imaging Collaboration https://doi.org/10.34970/2024-slice-3d (2024).

Creative Commons Attribution-Non Commercial 4.0 International License.

The dataset was generated by the International Skin Imaging Collaboration (ISIC) and images are from the following sources: Hospital Clinic de Barcelona, Memorial Sloan Kettering Cancer Center, Hospital of Basel, FNQH Cairns, The University of Queensland, Melanoma Institute Australia, Monash University and Alfred Health, University of Athens Medical School, and Medical University of Vienna.

#### Contact Detail(s)
<!-- scope: periscope -->
<!-- info: Provide pathways to contact dataset owners: -->
- **Dataset Owner(s):** International Skin Imaging Collaboration
- **Affiliation:** Hospital Clínic de Barcelona, Memorial Sloan Kettering Cancer Center, Hospital of Basel, FNQH Cairns, The University of Queensland, Melanoma Institute Australia, Monash University and Alfred Health, University of Athens Medical School, and Medical University of Vienna.
- **Contact:** contact@isic.org
- **Group Email:** contact@isic.org
- **Website:** https://www.isic-archive.com

#### Author(s)
<!-- scope: microscope -->
<!-- info: Provide the details of all authors associated with the dataset:

(Usage Note: Provide the affiliation and year if different from publishing
institutions or multiple affiliations.) -->
- 
Name                  	            Affiliation
Jochen Weber          	            Memorial Sloan Kettering Cancer Center
Kivanc Kose, Ph.D.                  Memorial Sloan Kettering Cancer Center
Allan Halpern, M.D.   	            Memorial Sloan Kettering Cancer Center
Maura Gillis          	            Memorial Sloan Kettering Cancer Center
Josep Malvehy, M.D.    	            Hospital Clinic de Barcelona
H Peter Soyer, Prof., M.D.	        the University of Queensland
Harald Kittler, Prof., M.D.	        Medical University of Vienna
Konstantinos Liopyris, M.D.	        University of Athens
Linda K Martin, M.D.	              Melanoma Institute Australia
Pascale Guitera, M.D.	              Melanoma Institute Australia
Alexander A Navarini, Prof., M.D.	  University Hospital of Basel
Victoria J Mar, M.D.	              Alfred Hospital
Vin Rajeswaran, M.D.	              FNQH Cairns
Noel Codella, Ph.D.	                Microsoft

### Funding Sources
#### Institution(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the funding institution(s): -->
-The International Skin Imaging Collaboration (ISIC), Canfield Scientific, Inc., Kaggle

#### Funding or Grant Summary(ies)
<!-- scope: periscope -->
<!-- width: full -->
<!-- info: Provide a short summary of programs or projects that may have funded
the creation, collection, or curation of the dataset.

Use additional notes to capture any other relevant information or
considerations. -->
The dataset was jointly funded and supported by The International Skin Imaging Collaboration (ISIC), Canfield Scientific, Inc., and Kaggle. This collaboration was formed as part of ISIC’s broader mission to improve the accuracy and accessibility of dermatologic diagnostics through the creation of public datasets, competitions, and research tools. While no specific grant numbers are cited, these institutions contributed resources toward the curation, annotation, and dissemination of the dataset, notably in support of challenges hosted on Kaggle.

https://challenge2024.isic-archive.com/

## Dataset Overview
#### Data Subject(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable**** subjects contained the dataset: -->
- Sensitive Data about people
- Health Data

#### Dataset Snapshot
<!-- scope: periscope -->
<!-- info: Provide a snapshot of the dataset:<br><br>(Use the additional notes
to include relevant information, considerations, and links to table(s) with
more detailed breakdowns.) -->
Category | Data
--- | ---
Size of Dataset | 2.69 GB
Number of Instances | 401064
Number of Fields | 55
Labeled Classes | Benign, Malignant
Number of Labels | broadly classified into 2
Average Labeles Per Instance | 400666 for benign and 393 for malignant


#### Descriptive Statistics
<!-- width: full -->
<!-- info: Provide basic descriptive statistics for each field.

Use additional notes to capture any other relevant information or
considerations.

Usage Note: Some statistics will be relevant for numeric data, for not for
strings. -->

Statistic | Width     | Height    | FileSize_KB
  ---     |    ---    |   ---     |     ---   
count     | 401059.00 | 401059.00 | 401059.00
mean      | 133.24531 | 133.24531 | 2.767635
std       | 18.271392 | 18.271392 | 0.581887
min       | 41.000000 | 41.000000 | 0.818359
25%       | 121.00000 | 121.00000 | 2.366211 
50%       | 131.00000 | 131.00000 | 2.721680
75%       | 143.00000 | 143.00000 | 3.117188
max       | 269.00000 | 269.00000 | 7.691406
mode      | 133.00000 | 133.00000 | 2.788086

**Above:** statistics of image dataset

### Sensitivity of Data
#### Sensitivity Type(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable*** data types present in the dataset: -->
- User Content
- User Metadata
- S/PII
- Anonymous Data
- Health Data


#### Field(s) with Sensitive Data
<!-- scope: periscope -->
<!-- info: List fields in the dataset that contain S/PII, and specify if their
collection was intentional or unintentional.

Use additional notes to capture any other relevant information or
considerations. -->
**Intentional Collected Sensitive Data**


| Field Name   | Type of S/PII               |
|--------------|-----------------------------|
| Age          | Indirect Identifier         |
| Sex          | Indirect Identifier         |
| Lesion Site  | Potential Identifier        |
| Diagnosis    | Health Data (Condition)     |

**Unintentionally Collected Sensitive Data**

None reported; all sensitive features were intentionally collected.

#### Security and Privacy Handling
<!-- scope: microscope -->
<!-- info: Summarize the measures or steps to handle sensitive data in this
dataset.

Use additional notes to capture any other relevant information or
considerations. -->

- **Pseudonymization:** Patient identifiers were removed and replaced with pseudonymous IDs.
- **Access Control:** Data is hosted on Kaggle requiring authenticated login for access.
- **IRB/Compliance:** Only de-identified data is used; dataset is compliant with institutional ethical approvals.


#### Risk Type(s)
<!-- scope: telescope -->
<!-- info: Select **all applicable** risk types presenting from the
dataset: -->
- Direct Risk
- Indirect Risk
- Residual Risk
- No Known Risks
- Others (Please Specify)

#### Supplemental Link(s)
<!-- scope: periscope -->
<!-- info: Provide link(s) for documentation pertaining to sensitive data in
the dataset: -->
https://challenge2024.isic-archive.com/

#### Risk(s) and Mitigation(s)
<!-- scope: microscope -->
<!-- info: Summarize the steps taken to identify and mitigate risks from PII
or sensitive information.

Use additional notes to capture any other relevant information or
considerations. -->
- **Risk type:** Indirect Re-identification  
  **Mitigation:** Aggregation of metadata and removal of personal identifiers.

- **Risk type:** Health Data Exposure  
  **Mitigation:** Hosted on secure platforms (Kaggle); only non-personally-identifiable health fields included.

### Dataset Version and Maintenance

### Maintenance Status
- **Current Version:** 1.0  
- **Last Updated:** April 2024  
- **Release Date:** April 2024  
- **Status:** Actively Maintained

#### Maintenance Plan
<!-- scope: microscope -->
<!-- info: Summarize the maintenance plan for the dataset:

Use additional notes to capture any other relevant information or
considerations. -->
- **Versioning:** Future versions will track corrections or additions in metadata or image labels.
- **Updates:** Annual refresh based on additional cases and diagnostics.
- **Errors:** Reported issues will be addressed via Kaggle Discussion or GitHub if opened.
- **Feedback:** User feedback is collected through Kaggle forums.


#### Next Planned Update(s)
<!-- scope: periscope -->
<!-- info: Provide details about the next planned update: -->
- **Version affected:** 1.0  
- **Next data update:** November 2024  
- **Next version:** 1.1  
- **Expected Changes:** Label refinement and inclusion of additional patients from new centers.

---

## Example of Data Points
#### Primary Data Modality
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Image Data


#### Sampling of Data Points
<!-- scope: periscope -->
<!-- info: Provide link(s) to data points or exploratory demos: -->

- Typical Data Point Link
- Outlier Data Point Link


#### Typical Data Point
<!-- width: half -->
<!-- info: Provide an example of a typical data point and describe what makes
it typical.

**Use additional notes to capture any other relevant information or
considerations.** -->
```json
{{
  "lesion_id": "ABC123",
  "image": "ISIC_000001.jpg",
  "age": 58,
  "sex": "male",
  "site": "upper_back",
  "diagnosis": "benign",
  "label": 0
}}
```

#### Atypical Data Point
<!-- width: half -->
<!-- info: Provide an example of an outlier data point and describe what makes
it atypical.

**Use additional notes to capture any other relevant information or
considerations.** -->
### Atypical Data Point

```json
{{
  "lesion_id": "XYZ987",
  "image": "ISIC_000987.jpg",
  "age": 85,
  "sex": "female",
  "site": "scalp",
  "diagnosis": "malignant",
  "label": 1
}}
```

## Motivations & Intentions
### Motivations
#### Purpose(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->

- Research

#### Domain(s) of Application
<!-- scope: periscope -->
<!-- info: Provide a list of key domains of application that the dataset has
been designed for:<br><br>(Usage Note: Use comma-separated keywords.) -->

- `Machine Learning`, `Medical Imaging`, `Skin Cancer Classification`

#### Motivating Factor(s)
<!-- scope: microscope -->
<!-- info: List the primary motivations for creating or curating this dataset:

(Usage Note: use this to describe the problem space and corresponding
motivations for the dataset.) -->
- Improve early detection of skin cancer using large-scale standardized photographic data.
- Support clinical diagnostics in real-world conditions where dermoscopic images are unavailable.

### Intended Use
#### Dataset Use(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Safe for research use
- Only approved use


#### Suitable Use Case(s)
<!-- scope: periscope -->
<!-- info: Summarize known suitable and intended use cases of this dataset.

Use additional notes to capture any specific patterns that readers should
look out for, or other relevant information or considerations. -->
**Suitable Use Case:** The dataset is ideal for developing and evaluating AI/ML models for:

Skin cancer classification: Predicting malignancy using images + clinical metadata.

Multimodal learning: Combining image data with structured metadata.

Weakly vs. strongly supervised learning: Handling mixed label reliability.

Explainable AI in healthcare: Understanding model decisions using interpretable features like asymmetry, color variation, etc.


#### Unsuitable Use Case(s)
<!-- scope: microscope -->
<!-- info: Summarize known unsuitable and unintended use cases of this dataset.

Use additional notes to capture any specific patterns that readers should look
out for, or other relevant information or considerations. -->
**Unsuitable Use Case:** 
Clinical Use: Not for real-world diagnostics or treatment.

Commercial Use: Prohibited under CC BY-NC 4.0 license.

Re-identification: Any attempt to identify individuals is not allowed.

Misuse of Results: Avoid overstating performance without noting dataset limitations.

#### Research and Problem Space(s)
<!-- scope: periscope -->
<!-- info: Provide a description of the specific problem space that this
dataset intends to address. -->
- Early detection of melanoma and other skin malignancies using full-body 3D TBP images.
- Addressing the challenge of low prevalence of malignant lesions in large population datasets.

#### Citation Guidelines
<!-- scope: microscope -->
<!-- info: Provide guidelines and steps for citing this dataset in research
and/or production.

Use additional notes to capture any specific patterns that readers should look
out for, or other relevant information or considerations. -->
**Guidelines & Steps:** 
Primary citation: https://www.nature.com/articles/s41597-024-03743-w
SLICE-3D ISIC 2024 Challenge Dataset. International Skin Imaging Collaboration (ISIC). https://slice-isic2024.grand-challenge.org/

**BiBTeX:**
```
@misc{slice3d2024,
  title = {SLICE-3D ISIC 2024 Challenge Dataset},
  author = {ISIC Challenge Team},
  year = {2024},
  note = {\url{https://slice-isic2024.grand-challenge.org/}},
  howpublished = {\url{https://slice-isic2024.grand-challenge.org/}}
}

```

## Access, Rentention, & Wipeout
### Access
#### Access Type
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- External - Open Access (via Kaggle)

#### Documentation Link(s)
<!-- scope: periscope -->
<!-- info: Provide links that describe documentation to access this
dataset: -->
- [Dataset Website](https://www.kaggle.com/competitions/isic-2024-challenge/data)

#### Prerequisite(s)
<!-- scope: microscope -->
<!-- info: Please describe any required training or prerequisites to access
this dataset. -->
N/A

#### Policy Link(s)
<!-- scope: periscope -->
<!-- info: Provide a link to the access policy: -->
- [Kaggle Terms of Use](https://www.kaggle.com/terms)

Code to download data:
```
!kaggle competitions download -c isic-2024-challenge

```

#### Access Control List(s)
<!-- scope: microscope -->
<!-- info: List and summarize any access control lists associated with this
dataset. Include links where necessary.

Use additional notes to capture any other information relevant to accessing
the dataset. -->
[\[Link\]]https://creativecommons.org/licenses/by-nc/4.0/

### Retention
- **Duration:** Indefinite
- **Retention Plan ID:** ISIC2024-RP1  
- **Summary:** The dataset will be maintained indefinitely for research reuse unless revoked by contributing institutions.

**Summary:** Write summary and notes here

#### Process Guide
<!-- scope: periscope -->
<!-- info: Summarize any requirements and related steps to retain the dataset.

Use additional notes to capture any other relevant information or
considerations. -->
For example:

This dataset compiles with [\[standard policy guidelines\]](https://creativecommons.org/licenses/by-nc/4.0/).



#### Exception(s) and Exemption(s)
<!-- scope: microscope -->
<!-- info: Summarize any exceptions and related steps to retain the dataset.
Include links where necessary.

Use additional notes to capture any other relevant information or
considerations. -->
**Exemption Code:** `ANONYMOUS_DATA` /
`EMPLOYEE_DATA` / `PUBLIC_DATA` /
`INTERNAL_BUSINESS_DATA` /
`SIMULATED_TEST_DATA`


### Wipeout and Deletion
- **Acceptable Means of Deletion:** Dataset hosted on Kaggle can be versioned down or removed upon request by data providers.
- **Post-Deletion Obligations:** None applicable for users; dataset deletion handled by ISIC.
- **Wipeout Integration Operational Requirements:** Must comply with publisher request (e.g., institution consent withdrawal).
- **Exceptions and Exemptions:** De-identified data is considered exempt from HIPAA and GDPR under current use cases.

#### Duration
<!-- scope: periscope -->
<!-- info: Specify the duration after which this dataset should be deleted or
wiped out: -->
N/A


## Provenance
### Collection
- **Method:** Collected using Canfield Vectra WB360 3D Total Body Photography system.
- **AI-assisted lesion detection** was used to crop and isolate skin lesion areas.
#### Method(s) Used
<!-- scope: telescope -->
<!-- info: Select **all applicable** methods used to collect data: -->
- Crowdsourced - Volunteer
- Vendor Collection Efforts


#### Methodology Detail(s)
<!-- scope: periscope -->
<!-- info: Provide a description of each collection method used.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for collection method
type.) -->
**Collection Type**

- **Source**: The dataset was collected by the International Skin Imaging Collaboration (ISIC) consortium across nine international dermatology centers. The 2D image crops were extracted from 3D Total Body Photography (TBP) images using the Vectra WB360 system from Canfield Scientific. AI-based software (Lesion Visualizer) automatically detected lesions and generated crops with metadata.  
  → Source reference: [Scientific Data publication](https://www.nature.com/articles/s41597-024-03743-w)

- **Platform**: [Vectra WB360 by Canfield Scientific](https://www.canfieldsci.com/imaging-systems/vectra-wb360-whole-body-imaging-system/). Lesions were identified using proprietary AI software called **Lesion Visualizer**, also developed by Canfield Scientific.


- **Is this source considered sensitive or high-risk?**: ✅ **Yes**  
  → Contains de-identified health information including age, sex, anatomical site, and clinical/pathological diagnoses.

- **Dates of Collection**: **Jan 2015 – Jan 2024**

- **Primary modality of collection data**:
  - ✅ **Image Data**
  - ✅ **Tabular Data** (Metadata: age, sex, diagnosis, location)
  - ⬜ Text Data
  - ⬜ Audio/Video
  - ⬜ Others


**Update Frequency for collected data:**

*Usage Note: Select one for this collection type.*

- Yearly



#### Source Description(s)
<!-- scope: microscope -->
<!-- info: Provide a description of each upstream source of data.

Use additional notes to capture any other relevant information or
considerations. -->
- **Source**:  
  Data was collected from 3D body scans and pathology-verified medical records at international medical institutions. Lesions were AI-annotated and manually reviewed by board-certified dermatologists.

- **Source**:  
  Strong labels were generated through histopathology within 3 months of image capture. Weak labels were clinical assessments by dermatologists.

- **Source**:  
  Data includes samples from Memorial Sloan Kettering Cancer Center, Hospital Clínic de Barcelona, University of Queensland, University of Athens, FNQH Cairns, Melanoma Institute Australia, Alfred Hospital, and Medical University of Vienna.

**Additional Notes**:  
- Dataset versions: **SLICE-3D** and **SLICE-3D Permissive**  
- Licensing: CC-BY-NC 4.0 (standard) and CC-BY 4.0 (permissive subset)  
- Website: [https://challenge2024.isic-archive.com](https://challenge2024.isic-archive.com)

#### Collection Cadence
<!-- scope: telescope -->
<!-- info: Select **all applicable**: -->
**Static:** Data was collected once from single or multiple sources.

**Streamed:** Data is continuously acquired from single or multiple sources.

**Dynamic:** Data is updated regularly from single or multiple sources.



#### Data Integration
<!-- scope: periscope -->
<!-- info: List all fields collected from different sources, and specify if
they were included or excluded from the dataset.

Use additional notes to
capture any other relevant information or considerations.

(Usage Note: Duplicate and complete the following for each upstream
source.) -->

- Dataset integrates images and metadata from nine institutions across three continents.
**Source**

**Included Fields**

Data fields that were collected and are included in the dataset.

Field Name | Description
--- | ---
target	  | Binary class {0: benign, 1: malignant}.
lesion_id | Unique lesion identifier. Present in lesions that were manually tagged as a lesion of interest.
iddx_full	| Fully classified lesion diagnosis.
iddx_1	  | First level lesion diagnosis.
iddx_2	  | Second level lesion diagnosis.
iddx_3	  | Third level lesion diagnosis.
iddx_4	  | Fourth level lesion diagnosis.
iddx_5	  | Fifth level lesion diagnosis.
mel_mitotic_index |	Mitotic index of invasive malignant melanomas.
mel_thick_mm	| Thickness in depth of melanoma invasion.
tbp_lv_dnn_lesion_confidence | Lesion confidence score (0-100 scale).+
isic_id	| Unique case identifier.
patient_id |	Unique patient identifier.
age_approx |	Approximate age of patient at time of imaging.
sex	 | Sex of the person.
anatom_site_general |	Location of the lesion on the patient's body.
clin_size_long_diam_mm	| Maximum diameter of the lesion (mm).+
image_type | Structured field of the ISIC Archive for image type.
tbp_tile_type |	Lighting modality of the 3D TBP source image.
tbp_lv_A |	A inside lesion.+
tbp_lv_Aex |	A outside lesion.+
tbp_lv_B |	B inside lesion.+
tbp_lv_Bext |	B outside lesion.+
tbp_lv_C	| Chroma inside lesion.+
tbp_lv_Cext |	Chroma outside lesion.+
tbp_lv_H	| Hue inside the lesion; calculated as the angle of A* and B* in LAB* color space. Typical values range from 25 (red) to 75 (brown).+
tbp_lv_Hext |	Hue outside lesion.+
tbp_lv_L |	L inside lesion.+
tbp_lv_Lext	| L outside lesion.+
tbp_lv_areaMM2 |	Area of lesion (mm^2).+
tbp_lv_area_perim_ratio |	Border jaggedness, the ratio between lesions perimeter and area. Circular lesions will have low values; irregular shaped lesions will have higher values. Values range 0-10.+
tbp_lv_color_std_mean |	Color irregularity, calculated as the variance of colors within the lesion's boundary.
tbp_lv_deltaA |	Average A contrast (inside vs. outside lesion).+
tbp_lv_deltaB |	Average  B contrast (inside vs. outside lesion).+
tbp_lv_deltaL |	Average L contrast (inside vs. outside lesion).+
tbp_lv_deltaLBnorm |	Contrast between the lesion and its immediate surrounding skin. Low contrast lesions tend to be faintly visible such as freckles; high contrast lesions tend to be those with darker pigment. Calculated as the average delta LB of the lesion relative to its immediate background in LAB* color space. Typical values range from 5.5 to 25.+
tbp_lv_eccentricity |	Eccentricity.+
tbp_lv_location |	Classification of anatomical location, divides arms & legs to upper & lower; torso into thirds.+
tbp_lv_location_simple |	Classification of anatomical location, simple.+
tbp_lv_minorAxisMM |	Smallest lesion diameter (mm).+
tbp_lv_nevi_confidence |	Nevus confidence score (0-100 scale) is a convolutional neural network classifier estimated probability that the lesion is a nevus. The neural network was trained on approximately 57,000 lesions that were classified and labeled by a dermatologist.+,++
tbp_lv_norm_border |	Border irregularity (0-10 scale); the normalized average of border jaggedness and asymmetry.+
tbp_lv_norm_color |	Color variation (0-10 scale); the normalized average of color asymmetry and color irregularity.+
tbp_lv_perimeterMM	Perimeter of lesion (mm).+
tbp_lv_radial_color_std_max |	Color asymmetry, a measure of asymmetry of the spatial distribution of color within the lesion. This score is calculated by looking at the average standard deviation in LAB* color space within concentric rings originating from the lesion center. Values range 0-10.+
tbp_lv_stdL |	Standard deviation of L inside lesion.+
tbp_lv_stdLExt |	Standard deviation of L outside lesion.+
tbp_lv_symm_2axis |	Border asymmetry; a measure of asymmetry of the lesion's contour about an axis perpendicular to the lesion's most symmetric axis. Lesions with two axes of symmetry will therefore have low scores (more symmetric), while lesions with only one or zero axes of symmetry will have higher scores (less symmetric). This score is calculated by comparing opposite halves of the lesion contour over many degrees of rotation. The angle where the halves are most similar identifies the principal axis of symmetry, while the second axis of symmetry is perpendicular to the principal axis. Border asymmetry is reported as the asymmetry value about this second axis. Values range 0-10.+
tbp_lv_symm_2axis_angle |	Lesion border asymmetry angle.+
tbp_lv_x |	X-coordinate of the lesion on 3D TBP.+
tbp_lv_y |	Y-coordinate of the lesion on 3D TBP.+
tbp_lv_z |	Z-coordinate of the lesion on 3D TBP.+
attribution |	Image attribution, synonymous with image source.
copyright_license |	Copyright license.


#### Data Processing
<!-- scope: microscope -->
<!-- info: Summarize how data from different sources or methods aggregated,
processed, or connected.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the following for each source OR
collection method.) -->
**Collection Method or Source**

**Description:** 
The ISIC 2024 Skin Cancer Detection dataset was sourced from the ISIC Challenge on Kaggle. It includes anonymized skin lesion images and metadata collected from multiple international healthcare institutions.

**Methods employed:** 

Checked for missing values and duplicates

Removed outliers using IQR

Normalized numeric metadata (Min-Max) and images (resized to 224×224, scaled to [0, 1])

Analyzed class distribution and feature distributions

Verified image integrity and brightness levels

**Tools or libraries:** pandas, numpy, matplotlib, seaborn, missingno, OpenCV, Pillow, scikit-learn

**Additional Notes:** 

Cleaned metadata saved as cleaned_metadata.csv

Dataset is imbalanced (more benign cases); handling strategies to be applied during modeling

No corrupt image files found

### Collection Criteria
#### Data Selection
<!-- scope: telescope -->
<!-- info: Summarize the data selection criteria.

Use additional notes to capture any other relevant information or
considerations. -->
- **Collection Method of Source:** Lesions were extracted from standardized 3D total body photography (TBP) images captured using the Vectra WB360 system. All selected lesions had corresponding metadata, and selection was automated using the TBP Lesion Visualizer system, which identified and cropped regions of interest.
- **Collection Method of Source:** Priority was given to lesions with available diagnostic outcomes and metadata fields such as sex, age, clinical site, and lesion size, to support multimodal ML analysis.
- **Collection Method of Source:** Only lesions from contributing institutions within the International Skin Imaging Collaboration (ISIC) network were considered for inclusion.

**Additional Notes:** Automated detection algorithms were employed to minimize bias in manual selection. Lesions lacking minimum metadata or ambiguous cropping results were discarded during preprocessing.

#### Data Inclusion
<!-- scope: periscope -->
<!-- info: Summarize the data inclusion criteria.

Use additional notes to capture any other relevant information or
considerations. -->
- **Collection Method of Source:** Included lesions had clearly defined and localized crops in 15x15mm field-of-view windows, consistent with the Vectra WB360 imaging specifications.
- **Collection Method of Source:** Metadata fields required for inclusion included age, sex, anatomical location, lesion ID, and imaging source.
- **Collection Method of Source:** Inclusion also required a confirmed diagnostic label (either strong – histopathology-based or weak – clinician-based).

**Additional Notes:** The dataset ensures demographic and geographic diversity by including data from nine clinical centers across three continents, spanning the years 2015 to 2024.
#### Data Exclusion
<!-- scope: microscope -->
<!-- info: Summarize the data exclusion criteria.

Use additional notes to capture any other relevant information or
considerations. -->
- **Collection Method of Source:** Lesions with poor image quality, occlusions, or ambiguous boundaries were excluded after visual and algorithmic QC.
- **Collection Method of Source:** Records with missing or inconsistent key metadata (e.g., age, anatomical site) were filtered out before dataset curation.
- **Collection Method of Source:** Duplicate lesions or crops with overlapping coordinates across scans or timepoints were also removed to ensure independence across instances.

**Additional Notes:** Images used in the validation/test sets were not drawn from patients included in the training set, ensuring patient-level disjoint partitions.

### Relationship to Source
#### Use & Utility(ies)
<!-- scope: telescope -->
<!-- info: Describe how the resulting dataset is aligned with the purposes,
motivations, or intended use of the upstream source(s).

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->
- **Source Type:** Clinical imaging centers using the Vectra WB360 scanner provided high-resolution TBP images with lesion annotations. These images were leveraged to create cropped datasets for lesion classification tasks.
- **Source Type:** Public health and cancer research organizations contributed clinical metadata and histopathological labels to enhance training and benchmarking.
- **Source Type:** Historical ISIC datasets served as reference baselines, but no direct reuse was applied unless harmonized via SLICE-3D standards.

**Additional Notes:** The dataset facilitates large-scale AI model development for early skin cancer detection in full-body imaging contexts.


#### Benefit and Value(s)
<!-- scope: periscope -->
<!-- info: Summarize the benefits of the resulting dataset to its consumers,
compared to the upstream source(s).

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->

- **Source Type:** TBP imaging standardization allows consistent model performance benchmarking across clinical contexts.
- **Source Type:** Combination of imaging and metadata offers rich context for multimodal AI models.
- **Source Type:** Longitudinal data (2015–2024) enables the study of imaging trends, lesion evolution, and population coverage over time.

**Additional Notes:** Permissive and non-commercial licensing variants (CC-BY and CC-BY-NC) support academic and open-source research.

#### Limitation(s) and Trade-Off(s)
<!-- scope: microscope -->
<!-- info: What are the limitations of the resulting dataset to its consumers,
compared to the upstream source(s)?

Break down by source type.<br><br>(Usage Note: Duplicate and complete the
following for each source type.) -->
- **Source Type:** Slight imbalance in class labels (malignant vs. benign) due to real-world prevalence required resampling and augmentation.
- **Source Type:** Some diagnostic labels are weak (clinician-based), potentially affecting ground truth fidelity.
- **Source Type:** Metadata completeness varies slightly across institutions, limiting some cross-institutional comparisons.

### Version and Maintenance
<!-- info: Fill this next row if this is not the first version of the dataset,
and there is no data card available for the first version -->
#### First Version
<!-- scope: periscope -->
<!-- info: Provide a **basic description of the first version** of this
dataset. -->
- **Release date:** 03/2024
- **Link to dataset:** [SLICE-3D Dataset v1.0](https://doi.org/10.34970/2024-slice-3d)
- **Status:** Actively Maintained
- **Size of Dataset:** 1.2 GB (Images), 40 MB (Metadata)
- **Number of Instances:** 401,059

#### Note(s) and Caveat(s)
<!-- scope: microscope -->
<!-- info: Summarize the caveats or nuances of the first version of this
dataset that may affect the use of the current version.

Use additional notes to capture any other relevant information or
considerations. -->
Data updates in the ISIC Archive may differ slightly from those used in the challenge datasets. Researchers are advised to reference challenge-specific downloads to ensure reproducibility.

**Additional Notes:** Metadata on ISIC Archive is subject to revision over time; citations should always refer to the exact version used.


#### Cadence
<!-- scope: telescope -->
<!-- info: Select **one**: -->
Static (Challenge version is frozen for reproducibility)

#### Last and Next Update(s)
<!-- scope: periscope -->
<!-- info: Please describe the update schedule: -->

- **Date of last update:** 03/2024
- **Total data points affected:** Initial release
- **Data points updated:** 0
- **Data points added:** 0
- **Data points removed:** 0
- **Date of next update:** N/A (Challenge version frozen)

#### Changes on Update(s)
<!-- scope: microscope -->
<!-- info: Summarize the changes that occur when the dataset is refreshed.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->
- **Source Type:** Any updates will only apply to the ISIC Archive version, not the challenge version.
- **Source Type:** Minor metadata corrections or updates may appear in the ISIC public collection, but not in SLICE-3D Kaggle release.
- **Source Type:** Future datasets may extend the SLICE-3D standard for additional competitions.

**Additional Notes:** Any update will be documented under a new DOI for reproducibility.

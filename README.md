# NLSTNatureSciData

This repository holds the necessary scripts and demonstrations for our Nature Scientific Data manuscript on enhancing the National Lung Screening Trial collection with various forms of annotations. 

This repository holds the following:  
<pre>
NLSTNatureSciData/
├── DataRecords/
│   ├── createNLSTSeg.ipynb   -- code to generate the NLSTSeg SEG and SR DICOM files 
│   └── createNLSTSybil.ipynb -- code to generate the NLSTSybil SR DICOM files 
├── TechnicalValidation/
│   ├── consistencyChecks/
│   │   ├── NLSTSegVsTS.ipynb        -- code to compare NLSTSeg lung lobe locations of the lesions with TotalSegmentator lung lobe locations
│   │   └── NLSTSegvsNLSTSybil.ipynb -- code to compare NLSTSeg lesion segmentations with the NLST-Sybil bounding boxes 
│   ├── technicalCompliance.ipynb    -- code to ensure the files are true DICOM files 
│   └── validateNLSTSegVolume.ipynb  -- code to compare the volume of the lesions in NLSTSeg using pyradiomics vs what the authors provided 
├── UsageNotes/
│   ├── parseSEGandSR.ipynb -- demonstration of how to download, read, and visualize the SEG and SR DICOM files 
├── LICENSE
└── README.md
</pre>


Deepa Krishnaswamy  
Brigham and Women's Hospital  
December 2025

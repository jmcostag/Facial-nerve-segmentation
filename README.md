# Project title: Facial-nerve-segmentation

Final project for the Building AI course

## Summary

Correct identification of the facial nerve during parotid surgery is essential to avoid injuring it. Conventional magnetic resonance imaging (MRI) sequences do not have sufficient spatial resolution to determine the trajectory of the intraparotid facial nerve. Our study proposes that the combination of high-resolution volumetric DESS and TSE-VFA MRI sequences may allow volumetric segmentation of the facial nerve, and IA can help us to identificate the nerve in MRI. This segmentation could be applied in the surgical planning of parotid tumour pathology, decreasing the risk of complications by facilitating direct visualisation of the intraglandular pathway of the facial nerve.

## Background

Surgery for parotid gland tumors has a relatively high complication rate. Among these, facial nerve paralysis has the greatest impact on quality of life.

The main problem is that visualization of the intraglandular course of the facial nerve with CT and MRI that are commonly used in clinical practice can only be approximated through indirect methods. In the last decade, several works have been published that have used high-resolution MR sequences that have allowed direct visualization of the intraparotid nerve, although it remains a challenge in the diagnostic technique given the complex anatomy of the nerve.

Our study aims to initiate a project in collaboration with the radiology, maxillofacial surgery and otorhinolaryngology departments of our hospital to validate these resonance techniques and to offer a preoperative mapping to plan a safe and effective surgery that minimizes the risks of facial nerve injury.

One of the main difficulties of our study is being able to correctly identify the facial nerve in imaging techniques. Initially, AI will be used to compare it with the radiologist's pre-surgical segmentation, and subsequently compare the two methods with the actual location of the nerve observed by the surgeon. In a second stage, the possibility of directly segmenting the facial nerve based on AI methods could be considered.

## How is it used?

Segmentation of the facial nerve will be carried out systematically by two independent radiologists. Each observer will weight the degree of satisfaction of their segmentation experience from 0 to 3 of least or greatest satisfaction depending on the sequences used. Systematically, each observer will obtain the segmentations of each case through each of the acquired sequences and also with the combinations of the DESS sequence with the others.

AI will be used to validate the reliability of the segmentation method by, on the one hand, a coregistration of the segmentations carried out by each of the radiologists in each patient and determining the degree of coincidence through a semiquantitative evaluation system that evaluates the percentage of matching segmentation pixels, classifying the coregistration as excellent, partial or poor if the match is respectively >75%, between 75-35% or <35% of the segmented pixels. On the other hand, the reliability of the segmentation will also be validated through a radio-surgical correlation in each case between the volumetric segmentation image and a calibrated photograph of the facial dissection in the surgical act. The degree of agreement will be subjectively classified as good, medium or insufficient by consensus between the radiologist and the surgeon.
   
## Data sources and AI methods

Patients will be obtained from the consultations of the maxillofacial surgery or otorhinolaryngology services of our hospital. Between 10 and 15 patients who are candidates for parotid surgery with benign tumors and who can undergo an MRI will be included.

The AI will evaluate the percentage of pixels in the identification of the facial nerve in the imaging technique and the coincidence between this, the study of the radiologist and the actual location of the nerve observed by the surgeon recorded by photography will be analyzed.

## Challenges

The time and price of the analysis are huge, so the first few months the study will progress slowly. On the other hand, if the branches of the facial nerve are thin or the tumor affects them, their identification is more difficult, and we will have to search for techniques to facilitate the analysis of the images by the radiologist and the AI.

## What next?

In the future, an AI combined with MRI could be considered so that the nerve is automatically identified with the imaging test. 3D reconstructions of the nerve could be performed and allow the surgeon to use a neuronavigator in selected cases. The final objective is to reduce the percentage of surgical injuries of the facial nerve. 


## Acknowledgments

This project is based on research carried out by the Radiology, Maxillofacial Surgery, Otorhinolaryngology and Biomedical Engineering departments of the Hospital Clinic in Barcelona, and led by Dr Medrano.

Divi V, Fatt MA, Teknos TN, Mukherji SK. Use of cross-sectional imaging in predicting surgical location of parotid neoplasms. J Comput Assist Tomogr. 2005 May-Jun;29(3):315-9. doi: 10.1097/01.rct.0000161758.25130.34. PMID: 15891497.  

Bray, T. J., Lim, E. A., Jawad, S., Kaur, S., Otero, S., Beale, T. J., ... & Morley, S. J. (2021). Negative-contrast neurography: Imaging the extracranial facial nerve and its branches using contrast-enhanced variable flip angle turbo spin echo MRI. arXiv preprint arXiv:2103.13200.  

Fujii H, Fujita A, Kanazawa H, Sung E, Sakai O, Sugimoto H. Localization of Parotid Gland Tumors in Relation to the Intraparotid Facial Nerve on 3D Double-Echo Steady-State with Water Excitation Sequence. AJNR Am J Neuroradiol. 2019 Jun;40(6):1037-1042. doi: 10.3174/ajnr.A6078. Epub 2019 May 23. PMID: 31122915; PMCID: PMC7028587.  

Guenette JP, Ben-Shlomo N, Jayender J, Seethamraju RT, Kimbrell V, Tran NA, Huang RY, Kim CJ, Kass JI, Corrales CE, Lee TC. MR Imaging of the Extracranial Facial Nerve with the CISS Sequence. AJNR Am J Neuroradiol. 2019 Nov;40(11):1954-1959. doi: 10.3174/ajnr.A6261. Epub 2019 Oct 17. PMID: 31624121; PMCID: PMC6856445.  

Chu J, Zhou Z, Hong G, Guan J, Li S, Rao L, Meng Q, Yang Z. High-resolution MRI of the intraparotid facial nerve based on a microsurface coil and a 3D reversed fast imaging with steady-state precession DWI sequence at 3T. AJNR Am J Neuroradiol. 2013 Aug;34(8):1643-8. doi: 10.3174/ajnr.A3472. Epub 2013 Apr 11. PMID: 23578676; PMCID: PMC8051441.  

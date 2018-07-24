# Talks

_All of the slide decks related to my talks_

### Deep learning based OCR engine for the Indus script

- [IDLI Talk on YouTube](https://www.youtube.com/watch?v=qPF1oR9yMNY)
- [ThoughtWorks Geek Night Talk on YouTube](https://www.youtube.com/watch?v=g7v4QaCD-UQ)
- **Abstract:** Computational epigraphy is an interdisciplinary area that combines computing and the study of ancient inscriptions. The main challenge or bottleneck faced in the field of epigraphical research is the lack of standardized corpora of the ancient scripts under study. Preparing such data from raw archaeological records, requires laborious human effort, expertise and a lot of time. Machine Learning has been used in the past to reduce human effort in epigraphical research, in problems such as classification and search for graphemic patterns. However, ML and in specific Deep Learning has not been applied yet, for the complementary task of corpus preparation. This talk will be focusing on how a deep learned pipeline architecture was designed to serve as an OCR (Optical Character Recognition) engine that is capable of reading the Indus script, one of the very ancient and undeciphered inscriptions of the Harappan Civilization. This pipeline takes as input, images of the undeciphered Indus script, as found in archaeological artifacts, and returns as output a string of graphemes, suitable for inclusion in a standard corpus.

- Slide deck used to present at a weekly [IDLI](https://www.facebook.com/groups/idliai/) session.
- Slide deck used to present at a monthly [GeekNight TW](https://twchennai.github.io/geeknight/) session, May 2017 edition (25th May 2017).

### Distributed Panorama Construction of High Resolution UAV Imagery Using Public Compute Nodes

- **Slide Deck:** https://docs.google.com/presentation/d/1P-qX7qzGlI3vbvqG5tUDFrUdL1Y8diXQL0QLaqvQ3pk/edit?usp=sharing
- **A video report of the architecture and implementation of this project:**

[![Home Automation System](https://img.youtube.com/vi/iWw4_Ub2lPw/0.jpg)](http://www.youtube.com/watch?v=iWw4_Ub2lPw)

- **YouTube:** http://www.youtube.com/watch?v=iWw4_Ub2lPw

- This project was done as part of the **Smart India Hackathon 2018 (Software Edition), under the Department of Space (Indian Space Research Organization)**.
- Our team **"WYSIWYG4"** won the **first prize** and also a cash award of **Rs. 1,00,000** at this hackathon.

- **Details:**
  - The raw remote sensing/optical imagery captured by UAVs almost always needs to be processed for generating a region panorama using image stitching.
    - The image stitching procedure generally involves various steps namely:
      - Feature detection for finding correspondences between images so that they may be considered for alignment
      - Image calibration for removing optical defects such as distortions, chromatic aberrations etc.
      - Image registration that involves feature matching to determine optimal alignment features
      - Image blending that involves executing the adjustments figured out in the calibration stage, combined with remapping of the images to an output projection
  - However, these images are typically of gigantic sizes due to which processing them takes a significant amount of time and hardware based computational resources. This leads to cumulative delays in preparation of the imagery data in a format that is useful for scientific or public use. Thus after determining those steps which do not have dependencies on the other steps of processing, the images can be divided into chunks of small size (say a few KBs) and these can be distributed among the devices owned by common people such as smartphones, or even desktops.
  - An app/software will utilize the resources of the mobile or desktop to perform processing on the small image chunk and send the results back to the servers. At the server end, the processed chunks are assembled together to get the final output for that processing stage.
  - **Press Coverage:**
    - **Times of India:** https://timesofindia.indiatimes.com/city/ahmedabad/six-winners-emerge-from-smart-india-hackathon/articleshow/63561717.cms?utm_source=whatsapp&utm_medium=social&utm_campaign=TOIMobile
    - **The Hindu:** https://www.thehindu.com/todays-paper/tp-national/tp-tamilnadu/5-teams-from-ssn-college-win-prizes/article23461319.ece
    - **SSN College of Engineering:** http://www.ssn.edu.in/?page_id=15246
    - **Winning Moment - Facebook Live (by Gujarat Technological University):** https://www.facebook.com/gtuoffice/videos/1786668221397028/?t=8798

### Pokemon World and Indus Valley Civilisation - The Analogy

- Slide deck used to present at:
  - Off-Site 2017 of Qube Cinema Technologies.
  - Deep Learning for Image and Text Analysis - AICTE Sponsored Faculty Development Programme, by the Computer Science and Engineering department, at SSN College of Engineering. [FDP - SSN](https://aicte-fdp-2017.ssn.edu.in/speakers)

- **V1**: https://docs.google.com/presentation/d/1C2peTKpVMQM1KuadNgPzR7dg_R7cqexP0B8VdifsfX4/edit?usp=sharing

- **V2**: https://docs.google.com/presentation/d/1FSodM6Qbzglhrn_VizEul-MkerEBhEQIHpXIgPZGlG4/edit?usp=sharing

- **V3 (FDP - SSN)**: https://docs.google.com/presentation/d/1YI6VKB-lWh5x7q23zfAEALaPbpKu9OqYYnwRIzwvZLg/edit?usp=sharing

- This talk will basically be dealing with how extremely similar deep learning techniques and architecture were applied to solve two extremely polar problems concerning two completely unrelated worlds; The OCR problem for the scripts of the Indus Valley Civilisation and the Image Captioning problem in the Pokemon world.
- **Basic Talk Proposal (Indus Scripts)**: https://anthillinside.talkfunnel.com/2017/15-deep-learning-based-ocr-engine-for-the-indus-scrip
- **Docs (Pokemon Image Captioning)**:
  - **Slides**:
    - https://github.com/tpsatish95/image-captioning/blob/master/slide.pdf
    - https://docs.google.com/presentation/d/1ZTL2_MTh1d8R_EvdEOX2MkVvgS_VjSDv-BV3mzl_c0c/edit?usp=sharing
  - **Report**: https://github.com/tpsatish95/image-captioning/blob/master/report.pdf
  - **Code**: https://github.com/tpsatish95/image-captioning

- **Outline** - Points of Analogy:
  - The what, why, how (the DL architecture devised) of both problems
  - Analogy 1: (Region of Interest Extraction problem - classify Text/No-Text/Both, Pokemon/Other/Part)
    - IVC: Region Proposal + Text Region Extraction
    - PW: Pokemon Localisation
  - Analogy 2: (Classification Problem - to identify the Symbols, Actors / Actions)
    - IVC: Symbol Segmentation + Identification
    - PW: Pokemon Classification + Attack Classification
  - Analogy 3: (Sequence Generation Problem - to generate Numbers, Words)
    - IVC: Sequence of Numbers
    - PW: Attacker-Attack-Victim Sequences

- **Note:** The final slide deck will have the Indus Scripts OCR problem as the base and will be drawing analogies to the Pokemon Image Captioning problem wherever appropriate. This talk will also scratch the surface of the basic concepts like CNN, Transfer Learning and whatever is being used in both of these problems.

### Machine Learning from a Computer Vision and Natural Language Processing perspective

- Slide deck used to present at the Off-Site 2016 of Qube Cinema Technologies.

### Python Hands-on Workshop

- Slide deck used at a one day hands-on python workshop, conducted as a part of SSN ACM Student Chapter (2016 and 2017).

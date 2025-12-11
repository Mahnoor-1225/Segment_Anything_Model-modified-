The following is the link to the research papers related to it:
1) https://ai.meta.com/sam3d/
2) https://ai.meta.com/research/publications/sam-2-segment-anything-in-images-and-videos/
3) https://ai.meta.com/research/publications/sam-3-segment-anything-with-concepts/ 
# Segment Anything (SAM) Evolution: From Promptable Visual Segmentation to Concept-Driven A.I.

A comprehensive overview and resource repository for the Segment Anything Model (SAM) and its successors, SAM 2 and SAM 3, developed by Meta AI. This project summarizes the progression of foundation models for image and video segmentation.

## 🚀 Project Highlights

This repository focuses on the three major releases in the Segment Anything series:

| Model | Core Task | Key Advancement |
| :--- | :--- | :--- |
| **SAM** | Promptable Image Segmentation | Foundation model for *zero-shot* segmentation with visual prompts (points, boxes). |
| **SAM 2** | Promptable Visual Segmentation (PVS) | Extends SAM to **real-time video** segmentation using a streaming memory mechanism. |
| **SAM 3** | Promptable Concept Segmentation (PCS) | Enables **open-vocabulary detection** and segmentation of concepts using **text prompts**. |

---

## 📦 Segment Anything Model (SAM)

The foundational model that introduced a new paradigm for image segmentation.

### Core Concepts
* **Task:** The project introduced the **Promptable Segmentation** task, where the goal is to return a valid segmentation mask given *any* segmentation prompt (points, boxes, or text).
* **Model Architecture (SAM):** Composed of three components: a powerful image encoder, a flexible prompt encoder, and a fast mask decoder.
* **Ambiguity Handling:** To resolve ambiguity from a single prompt (e.g., a single click), SAM predicts **3 separate masks** corresponding to different levels of object granularity (whole object, a part, and a sub-part).
* **Dataset:** Trained on **SA-1B**, a massive dataset containing over 1 billion masks on 11 million licensed images.

---

## 📹 SAM 2: Segment Anything in Images and Videos

SAM 2 is the successor that extends the model's capabilities to the temporal domain, enabling unified segmentation in both images and videos.

### Key Features
* **Unified Vision:** Solves **Promptable Visual Segmentation (PVS)** in both static images and dynamic videos.
* **Real-Time Video:** Uses a **streaming memory mechanism** to process video frames sequentially while maintaining contextual awareness of past interactions and objects. * **Performance:** It demonstrates improved accuracy and is up to **6x faster** than the original SAM for image segmentation tasks.
* **Dataset:** Trained on the **SA-V (Segment Anything Video)** dataset, the largest video segmentation dataset to date.

---

## 💡 SAM 3: Segment Anything with Concepts

SAM 3 advances the series by integrating concept understanding, shifting from purely visual prompts to open-vocabulary concept segmentation.

### Key Features
* **New Task:** Introduces **Promptable Concept Segmentation (PCS)**.
* **Concept Prompts:** The model can segment objects based on **concept prompts**, defined as either short noun phrases (e.g., "yellow school bus") or image exemplars.
* **Open-Vocabulary Detection:** SAM 3 is designed to detect and segment **all instances** of a specified concept in an image or video simultaneously.
* **Architecture:** A unified model that combines an image-level detector and a memory-based video tracker (inherited from SAM 2) that share a single vision backbone.
* **Dataset:** Trained on the **Segment Anything with Concepts (SA-Co)** dataset, which features 4 million unique concept labels.

---

## 🔗 References and Official Papers

### Main Papers:
* **Segment Anything (SAM):** [Kirillov_Segment_Anything_ICCV_2023_paper.pdf] (Uploaded File)
* **SAM 2: Segment Anything in Images and Videos:** [SAM 2: Segment Anything in Images and Videos](https://ai.meta.com/research/publications/sam-2-segment-anything-in-images-and-videos/)
* **SAM 3: Segment Anything with Concepts:** [SAM 3: Segment Anything with Concepts](https://ai.meta.com/research/publications/sam-3-segment-anything-with-concepts/)

### Supplemental Information:
* General Q&A on SAM's Architecture and Technical Details

This video provides an interview with the engineers behind SAM 3 for a deeper understanding of the new concept-based segmentation capabilities: [What is Segment Anything 3 (SAM3)? Live Q&A with Meta's Engineers Behind the Model](https://www.youtube.com/watch?v=IATrWxEDpu4).


http://googleusercontent.com/youtube_content/0

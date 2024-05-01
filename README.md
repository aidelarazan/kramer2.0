# Narrative coherence facilitates and reorganizes the timeline of realistic event recall
Angelique I. Delarazan, Elena Bosak, Brendan I. Cohn-Sheehy, Jeffrey M. Zacks, and Zacharaiah M. Reagh

## Project Description
[PsyArXiv Preprint](https://osf.io/preprints/psyarxiv/dfxbg)

How are our everyday memories structured? Standard laboratory paradigms such as list-learning tasks have shown that recall clusters based on temporal context and semantic relationships between items. Understanding whether these phenomena observed in remembering isolated words or objects manifest in daily life—a realm often characterized by narrative threads of interconnected experiences--has only recently become a focus among memory researchers. Here, we investigate how time and narrative coherence influence the organization of recall, as well as memory for the timing of naturalistic experiences. Participants encoded picturebook-style stories that included multiple side plots. Some of these connected across time to form a single overarching narrative (Coherent Narratives) while others did not (Unrelated Narratives). We systematically varied the number of intervening events between connected narrative elements. Across three experiments using multiple recall tasks, Coherent Narratives were consistently better remembered than Unrelated Narratives. Critically, this narrative coherence benefit occurred regardless of the temporal distance between connected events. Narrative coherence did not directly influence memory for temporal location or distance but distorted the temporal organization of events during free recall: meaningfully connected events were recalled closer together than they appeared in the story. These findings reveal that people leverage meaningful connections between events when constructing memories from naturalistic experiences, affecting what is recalled and in what order. 

Repository includes: experiment code, data, and analyses notebooks.

### Experimental Design
**Encoding:** Participants were presented with a fictional story in the form of audio narration accompanied by static illustrations. The story is centered on a main character who interacts with four side-characters whose appearances (sideplot events) are unrelated to events that are central to the main character’s story (mainplot events). Each side-characters appears in two temporally-distant, distinct sideplot events that are separated by four or twelve intervening events (i.e., **Short Lag** or **Long Lag**, respectively). This lag between sideplot events was directly manipulated in order to investigate the influence of temporal proximity on memory. Furthermore, the two sideplot events involving each recurring side-character could either form one larger **Coherent Narrative**, in which meaningful links could be drawn between events, or separate **Unrelated Narratives**, in which no meaningful links could be drawn between events other than sharing a recurring side-character.

**Retrieval:** Participants completed different recall tasks and temporal judgement tasks across three experiments: 

**Recall Tasks**
  * Character-Cued Recall Task (Experiment 1 and 2). For each character in the story, participants were instructed to recall everything they could remember involving the character in as much detail as possible. Participants were presented with the character’s name and face onscreen, with a box for typing recall. Participants were required to spend a minimum of three minutes for each side-character and six minutes on the main character. Character cues were randomized for side-characters across participants, but the main character was always cued last.
  * Free Recall Task (Experiment 3). This task was aimed at assessing how participants organize their recall in the absence of cues, by asking participants to freely recall the entire story in any order. Participants were first shown a single screen containing the images of all story characters (side characters, main character, minor characters within main plot events). Participants were then presented with a blank screen with a text box, and they were prompted to recall as much of the story as possible, even minor details. Participants were required to spend a minimum of fifteen minutes on this task and encouraged to continue typing as long as they remember additional details.
    
**Temporal Judgment Tasks**
* Event Distance Task (Experiment 1). Participants were prompted with pairs of distinct images from different story events and instructed to estimate the distance between them. Participants used their mouse cursor to drag a slider on a continuous line ranging from all possible distances between pairs (scale of 1-142 events apart), and then they pressed the Continue button onscreen to submit their final response.
* Timeline Task (Experiment 2). Participants were presented with images from the story and instructed to determine when the image appeared within the timeline of the full story. Participants used their mouse cursor to drag a slider on a continuous line ranging from all possible timepoints (scale of 1-144 events) and pressed the Continue button to submit their final response.

## Folder Structure
 * [data](./data/)
 * [scripts](./scripts/)
    * [analyses](./scripts/analyses/)
    * [experiment](./scripts/experiment/)
 * [README.md](./README.md)

## Contact
Angelique I. Delarazan | a.delarazan@wustl.edu 

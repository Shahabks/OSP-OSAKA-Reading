## Technical Narrative of OSP for UPs-OSAKA

### This version of OSP is customized for UP, an English School in Osaka-Japan. This version can measure the “Reading Rate” of a speaker and compare it with the average rate of non-native and native speakers.


In this narrative, we explain how Mysol’s OSP-Reading-Rate works and look at the factors which influence the users’ Reading-Rate.
The chief goal is to deploy Mysol’s OSP-Speaking-Rate in three phases, by which we measure the users’ Speaking-Rate, a critical component of the language delivery. 
In phase-1, we focus on measuring only five types of suprasegmental features in utterances.

Inappropriate pausing         (IP)
Absence of pausing            (AP)
Absence of CV linking         (AL)
Inappropriate lexical stress  (ILS)
Inappropriate intonation       (II)

The scientific way to measure one’s Reading/Speaking rate is in syllables per second. 
OSP’s estimate of the “Reading Rate” is obtained by timing the user while reading a selection of text with a known syllables count.
OSP evaluates the competency of the user by employing mathematical formulas and ETS’s independent speaking rubrics and philosophy (Educational Testing Service-USA). 
OSP went through a Machine learning session, with an audio dataset of non-native and native English speakers. These audios ranged from just 2 minutes in length to just under 5 minutes. Speakers' topics were widely variable. 

Note, this is not the ”Speaking Rate”. Even if the user reads out loud, it’s not the same thing as a speaking rate.
The best way to determine the user’s speaking rate is to time the user’s delivering a free speech. 
All the annotations that will been analyzed by the current OSP-Reading are based on the mentioned rubrics and the non-native English speaker audios. We do not claim that these are 100% accurate or the only way the speech can be analyzed. We will upgrade the OSP algorithm. Your comments and feedback are most welcome. Please feel free to contact us and let us know your thoughts about the corpus.. 

Step 1. Find a quiet place for recording Make sure to turn off all background machinery and electronic appliances, such as your mobile phones or TV set.
Step 2. Set up your recording equipment
	Plug in and test your microphone. Please do not put the microphone too close to your mouth(10-12 inches from the speaker is preferred)to avoid “p pops
Step 3. Adjust the recording settings Before starting your recording, you must be certain that your machine sound recorder will record at DVD quality mono settings (44.10 kHz., 24-bit, mono).

For each session of the student training, we recommend teachers select five types of sentences:
wh- questions, 
declarative sentences, 
yes-no questions, 
tag questions 
closed-choice alternative questions
which can help eliminate or counterbalance the effects of different sentence types on suprasegmental features produced by learners and reveal the segmental features in different sentence types. 
The following five sentences corresponding to these sentence types were selected for further acoustic analysis. 

## A quick perfrmance report on ML

<table border="1">
  <tr>
    <th>Dataset</th>
    <th>Metric</th>
    <th>Accuracy</th>
    <th>Precision</th>
    <th>Recall (Sensitivity)</th>  
  </tr>
  <tr>
    <td>For native</td>
    <td>Reading Rate</td>
	<td>70%</td>
	  <td>83%</td>
	  <td>68%</td>
  </tr>
  <tr>
    <td>For Japanese-English speaker</td>
    <td>Reading Rate</td>
	<td>84%</td>
	  <td>88%</td>
	  <td>95%</td>
  </tr>
</table>




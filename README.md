# airport_chronicles
I will be exploring the importance of making visual-only videos accessible and outline the best practices for creating effective text transcripts that bridge the gap between visual media and accessibility. 
Following W3C guide, SC 1.2.1: ... Video-only (Prerecorded), this will review the test rules for non-streaming video elements that don't have any audio include:

a. Visual Information in Transcript: All the important visual content in the video should be described in a text transcript.
b. Applicability: This rule applies to any non-streaming video that's visible and has no accompanying audio.
c. Expected Outcome:
    The visual information should be available in a text transcript.
    This transcript should be accessible, either on the same page or linked, and included in the accessibility tree (so assistive technologies can easily access it).
    
Additionally, it's assumed that:
a. There is a way for users to start the video.
b. The video element isn't just displaying a static poster image.

Thus, if a visible, non-streaming video lacks audio, all its visual information must be described in a text transcript that is accessible and available on the page or linked.
This ensures that users relying on assistive technologies can understand the content despite the absence of audio.

To illustrate this, I will use a video I created called “Airport Chronicles.” By adhering to WCAG test rules for non-streaming video elements without audio and examining some of their examples, I identified aspects where the videos not only fail the tests but also lack in accessibility. 

Testing each video with a screen reader (Narrator) revealed that videos initially identified as passing for non-streaming video elements without audio were missing many accessible elements necessary for smooth screen reader interaction.

# WanderAR-thesis
WanderAR: The Use of Augmented Reality in Locating and Virtually Replicating Landmarks

## Abstract
Recent developments in the field of navigation focus on creating a more and
more immersive experience for the users, one that requires as little effort as possible
and is as effective and reliable as it can be. Augmented reality is one of the core
technologies used in this evolution due to its ability to create aiding elements that
seemingly blend with the real world. While this direction centres on ease of use
and time-saving, it takes away from the human creativity, curiosity, and experiences
that some travellers are seeking when finding themselves in a new environment.
Moreover, studies have shown that over-reliability on such navigation systems is
detrimental to the innate abilities of wayfinding and spatial orientation, critical in a
lot of limit situations.

This thesis proposes an original solution for both issues, which takes the very
same technology, and uses it to create a similarly immersive experience that allows,
in contrast, every individual more freedom to make their own decisions while navigating:
AR landmark navigation. This method emphasizes the end goal of the journey
by presenting spatially accurate outlines of a landmark, based on the geographic
data of the camera and landmark. This projection can be seen through physical obstacles
even if the user has no line of sight of the target. This offers enough cues
to convey the surrounding context while still offering a challenging experience that
forces users to engage with the world around them. In the long term, this approach
is believed to improve spatial recognition and orientation.

In the first two chapters of this thesis, we will study the theoretical aspects of
this method: the developments of the technology on top of which it is built and the
issues it tries to resolve, and we lay down the mathematical foundations that allow
us to convert real geographical data to the virtual world. In the third and fourth
chapters, we presentWanderAR, an Android application that exemplifies how such
a technology can be used to create a new exciting travelling experience for users by
allowing them to create routes composed of multiple landmarks, visualise them in
different modes and even create their own, personal landmarks for places of interest.

The implementation is client-server to allow for scalability and to delegate the
depositing of hefty landmark models away from the storage limitations of mobile
devices. The client was implemented using Unity and the server exposes an API
written with ASP.NET Core 6 which connects the client to a SQL Server database.

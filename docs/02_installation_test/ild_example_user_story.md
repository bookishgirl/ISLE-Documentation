## Testing ISLE -- 

Alice is curious about ISLE and wants to know more about using Islandora for her university's digital collections.  She does not have access to a server and would like to test drive Islandora before deciding whether or not to move forward with it.

Alice has a Windows 10 laptop and she has confirmed that it meets the [Host Server Specifications](../01_installation_host_server/../01_installation_host_server/host_server_system_specifications.md) for testing ISLE.  She also has Administrator rights on her laptop.

She begins by installing Docker for Windows and configuring her system so ISLE can run on it by following the [Install Docker for Windows](../01_installation_host_server/software-dependencies.md) instructions.  Next, Alice starts the services that make up ISLE and installs Islandora on a virtual machine running on her laptop using the [Test/Demo ISLE Installation Guide](ild_installation_guide.md).  Because this is a test site that can only be viewed on Alice's laptop, she does not need to make many config file changes and is safe using default settings.

Alice now has a working version of ISLE running on her laptop!  She can ingest new objects, view and edit exising objects, and safely test new settings.  When she is done testing, she can easily shut down ISLE with a single command, then start it again just as easily at another time to continue testing or demo it to colleagues.  If she decides to wipe out all of the changes she has made and start over with a fresh installation, she just has to delete the ISLE directory on her laptop and download the ISLE containers again--a process that usually takes no more than several minutes.

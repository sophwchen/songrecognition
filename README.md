# Week1Capstone

Loading Songs to Database

1. go through mp3 in our songs directory
2. digitize samples
3. peaks
4. fingerprinting
5. upload to database

User Workflow

1. choose to record from mic/upload an mp3 file (UI)   
2. digitize samples (audio to samples): input file path (str), output np array
3. peaks: input np array, ouput array of tuples
4. fingerprinting: input array of tuples, output ((fi,fj,tji),ti)
5. matching: input list of fingerprints, return match (if there is one)


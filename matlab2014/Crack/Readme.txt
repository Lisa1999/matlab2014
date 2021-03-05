x64 only  ~  feel free to patch the x86 versions or either libmwservices.so/libmwservices.dylib if you like   ....:-)
1) Mount Matlab 2014a UNIX disc and run the appropriate installer for either Linux(UNIX) or MAC OS X


2) choose "install manually without using the internet"		

3) when prompted to enter the "file installation key" use
    12345-67890-12345-67890  ( 20 digits Nothing special... you can use vvlmv's key if you like  12313-94680-65562-90832  )

4) pick the toolboxes you want to install ( they should all be avalible)

5) select activation without internet and use "license_405329_R2014a.lic" as license file.   ( Nothing special in the license, It's just one I used when experimenting )

For:
 
Linux   Copy/overwrite libmwservices.so ( from the linux folder provided ) to : /usr/local/MATLAB/R2014A/bin/glnxa64.. ( or where ever you have installed MATLAB .. this path would be from Ubuntu for example) As you're using linux, I don't have to explain user owned files vs root owned files ... right ? 

MAC OS X   Copy/overwrite libmwservices.dylib ( from the MAC OS X folder provided) to : \MATLAB_R2014a.app\bin\maci64 

Interestingly for both Linux and MAC OS X, the compiler seems to run just fine with no other files patched. ( unlike windoze) There are a couple of other FLEXLM'd files ( libinstutil.so ( linux), but I haven't discovered are problems.. please feel free to experiment.


Note: Install.jar is from vvmlv's windoze release... that's the beauty of JAVA... it's OS independant... ( actually that's the only good thing about JAVA....LOL)   


(Use it or not ... it's up to you... I had some time to waste one day and a colleague of mine had a Macbook pro that he wanted to use... having said that , it seems to run slower than the windoze version)


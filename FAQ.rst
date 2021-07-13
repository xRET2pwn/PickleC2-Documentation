#####################################
FAQ (Frequently Asked Questions)
#####################################

In this section I will try to cover to most common questions.

**********************************************************************
What will happen if the implant is up and running but the C2 is down?
**********************************************************************

Do not worry you will not lose your shell and all you need to do is re-run the C2 and load the listener again to interact with your implant




************************************************************************
HTTP is no encrypted so why i use it?
************************************************************************

Yes the standard http is not encyrypted but all the communication in the PickleC2 is encyrpted by AES.


************************************************************************
Why I can't Invoke a powershell script through powershell command?
************************************************************************

Because I uses Sytem.Diagnostics.ProcessStartInfo in the current powershell implant so when you invoke a powershell script it opens a new powershell session to execute your command which is invoke and after executing the command it will close the session. if you want to invoke a powershell script you need to use ``module`` option. 


.. raw:: html
   :file: buymeacoffe.html
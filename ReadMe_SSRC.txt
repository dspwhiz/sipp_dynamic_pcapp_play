Sometimes you need to  play different pcaps (like dtmf pcaps) captured from different sources. SIPP do sends all the pcaps    but SUT will ignore the subsequent pcaps as SSRC does not match. 
The patch is on top of sipp_dynamic_pcapp_play and sipp-3.3.

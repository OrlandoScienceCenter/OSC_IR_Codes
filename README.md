# OSC_IR_Codes
OSC Relevant Infrared Remote Codes

/* IR Codes: 

SOS 4x Projectors: 
  
  Send this once for ON, send twice with a one second delay between them for OFF
  irsend.sendNEC(0xCC0000FF, 32);

BenQ AR Sandbox:

  Send this once for on:
  On:
  Received NEC: CF20D

  Send this twice with a 1s delay between for off:
  Off:
  Received NEC: C728D
  
  Source:
  Received NEC: C20DF
  
  Enter:
  Received NEC: C08F7

  Menu/Exit:
  Received NEC: CF00F

  Up: 
  Received NEC: CD02F

  Down:
  Received NEC: C30CF
  
  Left: 
  Received NEC: CB04F

  Right:
  Received NEC: C708F

  Network Setting:
  Received NEC: C817E

  Network:
  Received NEC: C629D

SOS Projector High:

  Power:
  Received NEC: E172E817

  Keystone Up:
  Received NEC: E17204FB

  Keystone Down:
  Received NEC: E172847B
  
  Source:
  Received NEC: E17208F7

  Blank:
  Received NEC: E1728C73

Cobra Simulator Projectors:

  Off (Send Below Twice):
  Encoding  : NEC
  Code      : 4CB3748B (32 bits)

  On:
  Encoding  : NEC
  Code      : 4CB340BF (32 bits)

KT Kaleiedoscope Projectors:

  Send this once for on, twice with delay for off:
  Encoding  : UNKNOWN
  Code      : 2899206F (58 bits)

KT Theater:

  Standby:
  Encoding  : UNKNOWN
  Code      : 490ACFEF (50 bits)

  Power On:
  Encoding  : UNKNOWN
  Code      : 17670E53 (50 bits)

*/

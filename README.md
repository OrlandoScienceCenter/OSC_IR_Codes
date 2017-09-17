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
  Raw       : +9090 -4462 +576 -578 +554 -570 +552 -574 +548 -1702 +554 -1696 +550 -576 +556 -570 +552 -574 +548 -1702 +554 -572 +552 -574 +548 -1702 +554 -572 +548 -1700 +556 -1694 +550 -1700 +556 -570 +584 -542 +580 -1670 +576 -550 +582 -1668 +578 -548 +584 -542 +580 -546 +576 -1672 +582 -1668 +578 -548 +572 -1676 +580 -546 +576 -1674 +582 -1668 +576 -1672 +582 -544 +578 -546 +576 -552 +582 -544 +578 -550 +574 -552 +580 -544 +578 -548 +574 -1676 +580 -1670 +576 -1674 +580 -1668 +576 -1672 +582 -1668 +578 -1672 +584 -1668 +578 -14470 +9088 -2208 +604

  Power On:
  Encoding  : UNKNOWN
  Code      : 17670E53 (50 bits)
  Raw       : +9054 -4496 +574 -578 +556 -570 +552 -574 +548 -1700 +556 -1694 +552 -574 +550 -578 +556 -570 +552 -1698 +548 -576 +546 -578 +554 -1696 +550 -574 +548 -1702 +554 -1694 +552 -1698 +548 -576 +556 -570 +552 -574 +550 -1700 +556 -570 +554 -574 +548 -576 +546 -578 +554 -1696 +550 -1700 +546 -1704 +552 -572 +550 -1698 +548 -1702 +554 -1696 +550 -1700 +556 -570 +552 -574 +582 -544 +578 -548 +584 -540 +582 -546 +578 -548 +576 -550 +582 -1668 +578 -1672 +574 -1676 +582 -1668 +578 -1670 +574 -1676 +582 -1668 +578 -1672 +584 -14464 +9086 -2210 +604
  
Science Live Projector (Travelling Exhibit Hall):
  Power On/Off: Raw:  9041, 4507, 573, 1694, 573, 1694, 573, 573, 573, 573, 573, 573, 573, 573, 573, 573, 573, 1694,
 573, 1694, 573, 573, 573, 1694, 573, 573, 573, 1694, 573, 573, 573, 1694, 573, 573, 573, 573,
 573, 573, 573, 573, 573, 573, 573, 1694, 573, 573, 573, 573, 573, 1694, 573, 1694, 573, 1694,
 573, 1694, 573, 1694, 573, 573, 573, 1694, 573, 1694, 573, 573, 573, 40906
*/

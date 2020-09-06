# BBS-Color-Screen-Creator
This is a BBS color Screen creator, it takes ascii drawings and converts them to BBS code.

This program has ascii screens built in , just run the program and it will show you how to build an ascii
drawing that will work with my program. 

There are several reserved symbols that my program uses, for example.

_FULLSCREEN
CLS
PRINT
PRINT " ^-------------------------------------------------+"
PRINT " !               Main Message Menu                 !"
PRINT " *-------------------&-----------------------------="
PRINT " !       $           !                             !"
PRINT " *-------------------#-----------------------------="
PRINT " ! [C] Check Your Mail   [S] Scan Messages         !"
PRINT " ! [E] Enter New Message [J] Join Conference       !"
PRINT " ! [F] FILE MENU         [U] Update Settings       !"
PRINT " ! [G] Goodbye           [H] Help Level            !"
PRINT " ! [Q] Quit to Main Menu [?] Command Help          !"
PRINT " ! [R] Read Messages                               !"
PRINT " ~-------------------------------------------------%"
PRINT
PRINT "Pay special attention to the symbols on each corner"
PRINT "They are all different, one for each corner, to work"
PRINT "properly with my program , they must be right. The "
PRINT "rest of the characters also must be right except for"
PRINT "whats in the menu. You can see the other characters"
PRINT "that I use lines and connectors, the program turns"
PRINT "into nice corners and borders, for double corners "
PRINT "and borders, well , you can figure that one out."
PRINT
PRINT "Press any key to continue..."
DO WHILE INKEY$ = ""
LOOP

This is actually in my code and displays everytime you run it.

Here are some examples of my ascii drawings, actual examples.


^-------------------------------------------------------------------------+
!               Your BBS Name Goes Here        Main Menu                  !
*-------------------------------------------------------------------------=
!  [B] Bulletin Menu      [P] Page Sysop For Chat    [G] Goodbye          !
!  [C] Comments To Sysop  [Q] Questionaire Menu      [H] Help Menu        !
!  [D] Online Games Menu  [S] Stats On BBS           [J] Join Conference  !
!  [F] File Menu          [U] User List              [Y] Your Settings    !
!  [I] Initial Welcome    [V] Verify User            [?] Command Help     !
!  [L] Live Chat / Users  [W] Who Is Online          [M] Message Menu     !
!  [N] News Letter        [Z] Page Online User       [X] Internet Menu    !
*-------------------------------------------------------------------------=
!  [1] Run Screen Maker   [2] Run Config Editor                           !
~-------------------------------------------------------------------------%

    Conference : @CONF.NAME@
    Time Left  : @USER.TIMELEFTTODAY@    
    
    Main Menu Command >> 


^-----------------------------------------------------------------------------+
!   Sysop Menu                            Your BBS name Goes Here             !
*-------------------------------------------------&--&------------------------=
!^-----------------------------------------------+!  !^----------------------+!
!!                                               !!  !!    On Every Menu     !!
!! [A] Activity Logs      [Q] Quit To MAIN MENU  !!  !! [G] Goodbye          !!
!! [B] Broadcast Message  [S] Status of Database !!  !! [H] Help Level       !!
!! [F] File Database      [U] User Database      !!  !! [J] Join Conference  !!
!! [K] Kill Activity Logs [1] MESSAGE MENU       !!  !! [Y] Your Settings    !!
!! [N] Node Management    [2] FILE MENU          !!  !! [C] Config WCX Files !!
!! [V] View WILDCAT.LOG   [3] WtLord 2.9C Setup  !!  !! [?] Command Help     !!
!~-----------------------------------------------%!  !~----------------------%!
~-------------------------------------------------#--#------------------------%

    Conference : @CONF.NAME@
    Time Left  : @USER.TIMELEFTTODAY@

    Sysop Menu Command >>  
    
^--------------------------------------------------+
!                                                  !
! Internet Menu        Your BBS Name Goes Here     !
!                                                  !
*--------------------------------------------------=
!             [T] Telnet Outbound                  !
!             [F] FTP Outbound                     !
!                                                  !
!             [?] Info on Telnet and  FTP          !
!             [Q] Quit to Previous Menu            !
~--------------------------------------------------%

 You are about to establish a connection to an Internet host.
 The performance, reliability, availability and content of Internet
 hosts is beyond @SYSTEM.BBSNAME@'s control.

 Conference : @CONF.NAME@
 Time Left  : @USER.TIMELEFTTODAY@
 Command >>  
 
As you can see the ascii drawings are fairly simple, if you would like to become
a collaborator with this project, contact me.

Russ Campbell

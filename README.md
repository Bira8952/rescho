/*
==================================================================================================
   Script was generated with | FIFA 23 S.G.I && PES 23| ver. 1.0.9.68 | Date :10/09/24 | Time: 02:35:35 |
   Special thanks to DarkAngel - the author of one of the best new MODS                       
   Thanks to all Alpha Supporters!                         
==================================================================================================
==================================================================================================
| This Script was made and intended for www.cronusmax.com & CronusMAX ONLY.                       | 
| UNLESS permission is given by the creator and/or copywritee,                                    | 
| All rights reserved. This material may not be reproduced, displayed,                            | 
| modified or distributed without the express prior written permission of the                     | 
| copyright holder. For permission, contact CronusMax.                                            | 
|     __  ____   ___   ____   __ __  _____ ___ ___   ____  __ __                                  | 
|    /  ]|    \ /   \ |    \ |  |  |/ ___/|   |   | /    ||  |  |                                 | 
|   /  / |  D  )     ||  _  ||  |  (   \_ | _   _ ||  o  ||  |  |                                 | 
|  /  /  |    /|  O  ||  |  ||  |  |\__  ||  \_/  ||     ||_   _|                                 | 
| /   \_ |    \|     ||  |  ||  :  |/  \ ||   |   ||  _  ||     |                                 | 
| \     ||  .  \     ||  |  ||     |\    ||   |   ||  |  ||  |  |                                 | 
|  \____||__|\_|\___/ |__|__| \__,_| \___||___|___||__|__||__|__|                                 | 
|                                                                                                 | 
================================================================================================== 
==================================================================================================
*/
                                                                       
/*
       $$$$$$\  $$\       $$$$$$$$\ $$$$$$$\        $$\      $$\ $$$$$$$$\ $$\   $$\ $$\   $$\ 
      $$  __$$\ $$ |      $$  _____|$$  __$$\       $$$\    $$$ |$$  _____|$$$\  $$ |$$ |  $$ |
      $$ /  $$ |$$ |      $$ |      $$ |  $$ |      $$$$\  $$$$ |$$ |      $$$$\ $$ |$$ |  $$ |
      $$ |  $$ |$$ |      $$$$$\    $$ |  $$ |      $$\$$\$$ $$ |$$$$$\    $$ $$\$$ |$$ |  $$ |
      $$ |  $$ |$$ |      $$  __|   $$ |  $$ |      $$ \$$$  $$ |$$  __|   $$ \$$$$ |$$ |  $$ |
      $$ |  $$ |$$ |      $$ |      $$ |  $$ |      $$ |\$  /$$ |$$ |      $$ |\$$$ |$$ |  $$ |
       $$$$$$  |$$$$$$$$\ $$$$$$$$\ $$$$$$$  |      $$ | \_/ $$ |$$$$$$$$\ $$ | \$$ |\$$$$$$  |
       \______/ \________|\________|\_______/       \__|     \__|\________|\__|  \__| \______/ 
                                                                                               
*/
//====================================================
// DEVICE :  Cronus ZEN device 
//====================================================
//====================================================
// YOUR BUTTON LAYOUT : CLASIC
//====================================================
define ShotBtn       = PS4_CIRCLE; // Shot Btn         (default B/CIRCLE 
define PassBtn       = PS4_CROSS; // Short Pass Btn   (default A/CROSS)
define PlayerRun     = PS4_L1; // Player Run       (default L1/LB) 
define FinesseShot   = PS4_R1; // Finesse Shot     (default R1/RB)
define PaceCtrol     = PS4_L2; // Protect Ball     (default L2/LT)
define SprintBtn     = PS4_R2; // Sprint Btn       (default R2/RT)
define CrossBtn      = PS4_SQUARE; // Cross Btn        (default X/SQUARE)
define ThroughBall   = PS4_TRIANGLE; // Through Ball Btn (default Y/TRIANGLE) 
//====================================================
define MOVE_X        = PS4_LX;        
define MOVE_Y        = PS4_LY;        
define SKILL_STICK_X = PS4_RX;        
define SKILL_STICK_Y = PS4_RY;        
//====================================================
//-------------------------------------------------------------- 
// SKILLS LIST                                                   
//-------------------------------------------------------------- 
define None  = 0;
define FAKE_SHOT_SKILL                   = 1;
define HEEL_TO_HEEL_FLICK_SKILL          = 2;
define HEEL_FLICK_TURN_SKILL             = 3;
define RAINBOW_SKILL                     = 4;
define DRAG_BACK_SOMBRERO_SKILL          = 5;
define FAKE_PASS_SKILL                   = 6;
define DRAG_BACK_UNIVERSAL_SKILL         = 7;
define STEP_OVER_FEINT_SKILL             = 8;
define DRAG_TO_DRAG_SKILL                = 9;
define HOCUS_POCUS_SKILL                 = 10;
define TRIPLE_ELASTICO_SKILL             = 11;
define ELASTICO_SKILL                    = 12;
define REVERSE_ELASTICO_SKILL            = 13;
define CRUYFF_TURN_SKILL                 = 14;
define LA_CROQUETA_SKILL                 = 15;
define RONALDO_CHOP_SKILL                = 16;
define ROULETTE_SKILL                    = 17;
define FLAIR_ROULETTE_SKILL              = 18;
define BALL_ROLL_SKILL                   = 19;
define BERBA_MCGEADY_SPIN_SKILL          = 20;
define BOLASIE_FLICK_SKILL               = 21;
define TORNADO_SKILL                     = 22;
define THREE_TOUCH_ROULETTE_SKILL        = 23;
define ALTERNATIVE_ELASTICO_CHOP_SKILL   = 24;
define BALL_ROLL_CHOP_SKILL              = 25;
define FEINT_AND_EXIT_SKILL              = 26;
define FEINT_L_EXIT_R_SKILL              = 27;
define LATERAL_HEEL_TO_HEEL_SKILL        = 28;
define WAKA_WAKA_SKILL                   = 29;
define BODY_FEINT_SKILL                  = 30;
define DRAG_TO_HEEL                      = 31;
define BALL_ROLL_FAKE_TURN               = 32;
define FEINT_FORWARD_AND_TURN            = 33;
define TURN_BACK                         = 34;
define ADVANCED_CROQUETA                 = 35;
define CANCELED_THREE_TOUCH_ROULETTE_SKILL = 36;
define REVERSE_STEP_OVER_SKILL           = 37;
define FAKE_DRAG_BACK_SKILL              = 38;
define RAINBOW_TO_SCORPION_KICK_SKILL    = 39;
define STEP_OVER_BOOST_SKILL             = 40;
define CANCEL_SHOOT_SKILL                = 41;
define DIRECTIONAL_NUTMEG_SKILL          = 42;
define CANCELED_BERBA_SPIN_SKILL         = 43;
define CANCELED_BERBA_SPIN_WITH_DIRECTION = 44;
define BALL_ROLL_TO_SCOOP_TURN_SKILL     = 45;
define DRIBBLING_SKILL                   = 46;
define FOUR_TOUCH_TURN_SKILLS            = 47;
define SKILLED_BRIDGE_SKILL              = 48;
define SCOOP_TURN_FAKE_SKILL             = 49;
define BALL_ROLL_STEP_OVER_SKILL         = 50;
define CANCELED_4_TOUCH_TURN_SKILL       = 51;
define FAKE_SHOT_CANCEL_SKILL            = 52;
define OKKOSHA_FLICK_SKILL               = 53;
define ADVANCED_RAINBOW_SKILL            = 54;
define STOP_LA_CROQUETA_SKILL            = 55;
define JUGGLING_RAINBOW_SKILL            = 56;
define STOP_NEYMAR_ROLL_SKILL            = 57;
define STOP_V_DRAG_SKILL                 = 58;
define REV_OR_ELASTICO_SKILL             = 59;
define STOP_REV_OR_ELASTICO_SKILL        = 60;
define DRAG_REV_OR_ELASTICO_SKILL        = 61;
define FAKE_RABONA_SKILL                 = 62;
define RABONA_TO_REV_ELASTICO_SKILL      = 63;
define RABONA_TO_ELASTICO_SKILL          = 64;
define SOMBRERO_FLICK_SKILL              = 65;
define JUGGLE_BACK_SOMBRERO_SKILL        = 66;
define FAKE_BERBA_OPP_EXIT_SKILL         = 67;
define DIAGONAL_HEEL_CHOP_SKILL          = 68;
define FAKE_BERBA_FAKE_DRAG_SKILL        = 69;
define ELASTICO_CHOP_SKILL               = 70;
define BALL_ROLL_CUT_180_SKILL           = 71;
define HEEL_TO_BALL_ROLL_SKILL = 72;
define STUTTER_FEINT_SKILL = 73;
define JOG_OPENUP_FAKE_SHOT = 74;
/* Menu Variables */
int modMenu,editMenu; 
int modNameIdx,valNameIdx;

/* Display Variables / ScreenSaver / Strings/Text  */
int screenSaver,blankScreen;
int displayTitle = TRUE;
int updateDisplay;

const string Toggle  [] = {"Off","On"};
const string misc[]     = {"v1.18","Template",""}; 
const string AUTHOR  = "Excalibur";
const string VERSION = "V.1.0.9.68";
                        
/* Mod Menu Variables */
int TimedFinesFinish_on_off       ;// 0  TimedFines Finish
int UniversalPingToggle           ;// 1  Universal EA Ping
int TimedFinish_on_off            ;// 2  Timed Finish
int TimedTrivelaShot_Toggle       ;// 3  Timed Trivela
//--------------------------------------------------
                        
/* Adjustable Variables */
int tff_power                     ;// 0 
int tff_accuracy                  ;// 1 
int tff_ping                      ;// 2 
int tff_single_btn                ;// 3 
int EA_Ping                       ;// 4 
int tf_power                      ;// 5 
int tf_accuracy                   ;// 6 
int tf_ping                       ;// 7 
int tf_single_btn                 ;// 8 
int t_trivela_power               ;// 9 
int t_trivela_accuracy            ;// 10
int t_trivela_ping                ;// 11
int t_trivela_single_btn          ;// 12
//--------------------------------------------------
                        
//====================================================================
define MaxAmountOfMODs = 3;
//====================================================================
                        
//====================================================================
const int16 valuesMinMax[][] = {
//Min/Max/inc/dec             
{      1,    250,      1,     10,     0  }, // 0  tff_power
{      1,    250,      1,     10,     0  }, // 1  tff_accuracy
{      0,      1,      1,     10,     1  }, // 2  tff_ping
{      1,     21,      1,     10,    12  }, // 3  tff_single_btn
{      0,    300,      1,     10,     0  }, // 4  EA_Ping
{      1,    250,      1,     10,     0  }, // 5  tf_power
{      1,    250,      1,     10,     0  }, // 6  tf_accuracy
{      0,      1,      1,     10,     1  }, // 7  tf_ping
{      1,     21,      1,     10,    10  }, // 8  tf_single_btn
{      1,    600,      1,     10,     0  }, // 9  t_trivela_power
{      1,    250,      1,     10,     0  }, // 10 t_trivela_accuracy
{      0,      1,      1,     10,     1  }, // 11 t_trivela_ping
{      0,     21,      1,     10,    13  }  // 12 t_trivela_single_btn
}      
      
                    
//====================================================================
const int16 valRangeIdx[][] = {
// ValRangeMin - ValRangeMax - Editables 
{        0     ,       3     ,       1      }, // 0  TimedFinesFinish_on_off
{        4     ,       4     ,       1      }, // 1  UniversalPingToggle
{        5     ,       8     ,       1      }, // 2  TimedFinish_on_off
{        9     ,      12     ,       1      }  // 3  TimedTrivelaShot_Toggle
}// end of valRangeIdx 
                    
const uint8 toggleMax[] = {
3, // 0  TimedFinesFinish_on_off
1, // 1  UniversalPingToggle
3, // 2  TimedFinish_on_off
3  // 3  TimedTrivelaShot_Toggle
}

/*  
==================================================================================================================
 Const String Arrays                                                                                       
==================================================================================================================
*/                                                                                                                
const string modNames[] = { "TimedFines Finish","Universal EA Ping","Timed Finish","Timed Trivela", "" };
const string valNames[] = { "TFF Power","TFF Accuracy","TFF Ping","TFF Single Btn","EA Ping","TimedF Power","TimedF Accuracy","TimedFinish Ping","TimedF Single Btn","Trivela Power","Trivela Accuracy","Trivela Ping","Trivela SIngl Btn", "" };
const string PowerShootToggle_Opt [] = { "Disable","Single Button","Stand Full Power", "" };
const string TimedFinishToggle_Opt [] = { "Disable","Use Single Btn","Standard TF","TF Full Power", "" };
const string TimedFinesFinishToggle_Opt [] = { "Disable","Use Single Btn","Standard TFF","TFF Full Power", "" };
const string VMSpeedToggle_Opt [] = { "Disabled","XBOX ONE","PS4/PS5","XBOX  X/S","PC", "" };
const string RSSkillsToggle_Opt [] = { "Disabled","Always ON","DoubleTap Btn","Modifier Button", "" };

const string FinesseRestriction_Opt [] = { "Disabled","Use Single Btn","Standard Fin Shot","FinShot FullPower","" };
const string EnhancedMove_Opt [] = { "Disabled","EnhMove V. 4.0","EnhMove V. 4.1","" };
const string ExitDirection_Opt [] = {"Right","Left",""};
const string OneTap_DoubleTap_Opt[] ={"One Tap","Double Tap",""};
const string InstantSkills_Opt [] = { "Disabled","Modifier RS/R3","Modifier LS/L3","Modifier XB1 PR1","Modifier XB1 PR2","Modifier XB1 PL1","Modifier XB1 PL2", "" };
const string DribblingSens_Opt [] = { "Disabled","Dribbling Sens","Drbl+Sprint Sens", "" };
// Trivela Standard
const string TrivelaShotToggle_Opt[]={"Disabled","Single Btn","Trivela Restrict","Trivela FullPower",""}
const string SelectSkill[] = { "Disable","Fake Shot 3*","H to Heel Flick","Heel Flick Turn","Rainbow 4*","DragBack Sombrero","Fake Pass 4*","DragBackUniversal","Step Over Feint","Drag to Drag","Hocus Pocus","Triple Elastico","Elastico 5*","Reverse Elastico","Cruyff Turn 1*","La Croqueta","Ronaldo Chop","Roulette 3*","Flair Roulette 4*","Ball Roll 2*","Berb/Mcgeady Spin","Bolasie Flick","Tornado 5*","3 Touch Roulette","AlterntElast Chop","Ball Roll Chop","Feint and Exit 3*","Feint & Exit","Late Heel to Heel","WAKA WAKA","Body Feint 2*","Drag to Heel move","BallRollFake Turn","FeintForward&Turn","Turn Back 1*","Advanced Croqueta","Canc3TouchRoulete","Reverse Step Over","Fake Drag Back 5*","R toScorpionKick","Step Over Boost","Cancel Shoot 2*","Boost Dirc Nutmeg","Canc Berba Spin","C BerbaSpin+Direc","BallRoll-ScoopTrn","Dribbling Skill 2*","Four Touch Turn","Skilled Bridge 4*","Scoop Turn Fake","BallRoll-StepOver","Canc 4 Touch Turn","Fake Shot Cancel","Okocha Flick 5*","Advanced Rainbow","Stop La Croqueta","Juggling Rainbow","Stop-Neymar Roll","Stop & V Drag","Reverse/ Elastico","Stop-Rev/Elastico","Drag-Rev/Elastico","Fake Rabona","Rabona-Rev/Elasti","Rabona toElastico","Sombrero Flick","Jug BackSombrero","FakeBerbaOp Skill","DiagonalHeel Chop","FakeBerba-FDragBa","Elastico Chop 5*","Ball Roll Cut 180","Heel to Ball Roll","Stutter Feint 3*","Jog Openup F Shot", "" };
const string Select_btn_Opt[] = { "PS4_PS","PS4_SHARE","PS4_OPTIONS","PS4_R1","PS4_R2","PS4_R3","PS4_L1","PS4_L2","PS4_L3","PS4_UP","PS4_DOWN","PS4_LEFT","PS4_RIGHT","PS4_TRIANGLE","PS4_CIRCLE","PS4_CROSS","PS4_SQUARE","XB1_PR1","XB1_PR2","XB1_PL1","XB1_PL2","PS4_TOUCH", "" };
//===========================================================================
//    INITIALIZATION - INIT BLOCK
//===========================================================================
init {// init block start
   Load();
   if( ShootPower <= 0) ShootPower = 205;
   slot_numb = get_slot();
}// init block end
main { 
if(get_ival(PS4_L2)){
     if(event_press(PS4_SHARE)){
         EntireScript_On = !EntireScript_On;
         display_MOD_status(EntireScript_On,sizeof(SCRIPT_ONOFF)- 1,SCRIPT_ONOFF[0]);
         if(EntireScript_On) displayTitle = TRUE;
     }
 }
 if(time_to_clear_screen){
    time_to_clear_screen -= get_rtime();
    if(time_to_clear_screen <= 0)combo_run(CLEAR_SCREEN);
 }
 if(EntireScript_On ) {// Script code 
    LED_Color(Green);
    /* Enter Mod Menu */
    if(get_ival(PS4_L2)){ 
        if(event_press(PS4_OPTIONS)){ 
            modMenu = TRUE;
            updateDisplay = TRUE;
            displayTitle = FALSE;
            /* If NOT in Mod Menu - Display Title Screen Instead */
            if(!modMenu){ 
                displayTitle = TRUE;
            } 
        }
        set_val(PS4_OPTIONS,0);
    }
    /* If We are NOT on the Display Title - We are in The Mod Menu OR Edit Menu */
    if(!displayTitle){ 
        /* Mod Menu Navigation / Toggles */
        if(modMenu || editMenu){ 
            combo_run(rgb);
        } 
        if(modMenu){
            vm_tctrl(0);    
            /* Variables That We Can Turn On/Off Via The Menu */
			TimedFinesFinish_on_off       = toggleSwitch(TimedFinesFinish_on_off       ,0  );// 0 
			UniversalPingToggle           = toggleSwitch(UniversalPingToggle           ,1  );// 1 
			TimedFinish_on_off            = toggleSwitch(TimedFinish_on_off            ,2  );// 2 
			TimedTrivelaShot_Toggle       = toggleSwitch(TimedTrivelaShot_Toggle       ,3  );// 3 
            /* Navigate The Mod Menu */
            if(event_press(PS4_DOWN)){ 
                modNameIdx    = clamp(modNameIdx + 1,0,MaxAmountOfMODs);
                updateDisplay = TRUE;
            }
            if(event_press(PS4_UP)){ 
                modNameIdx    = clamp(modNameIdx - 1,0,MaxAmountOfMODs);
                updateDisplay = TRUE;
            }
            /* Exit The Mod Menu and Return To Display Title */
            if(event_press(PS4_CIRCLE)){ 
                modMenu       = FALSE;
                displayTitle  = FALSE;
                updateDisplay = FALSE;
                combo_run(MESSAGE); 
            }
            /* Enter The Edit Menu */
            if(valRangeIdx[modNameIdx][2] == 1){
                if(event_press(PS4_CROSS)){
                    valNameIdx    = valRangeIdx[modNameIdx][0];
                    modMenu       = FALSE;
                    editMenu      = TRUE;
                    updateDisplay = TRUE;
                } 
            } 
            BlockButtonPress ()
            //================================================
            // Display MOD 
            // display MOD : label with MOD number
            print( 2,38,OLED_FONT_SMALL, OLED_WHITE, MOD_LABEL[0]); 
            print_number(modNameIdx + 1 ,find_digits(modNameIdx + 1) ,28 , 38 , OLED_FONT_SMALL);
            
            // display Slot ; label and slot number
            print( 84,38,OLED_FONT_SMALL, OLED_WHITE, SLOT_LABEL[0]); 
            print_number(slot_numb ,find_digits(slot_numb) ,112 , 38 , OLED_FONT_SMALL); 
        
            line_oled(1,48,127,48,1,1); 
            if(valRangeIdx[modNameIdx][2] == 0 ){
                print( 2, 52, OLED_FONT_SMALL, 1, NO_EDIT_VARIABLE[0] ); 
            }else{
                print( 2, 52, OLED_FONT_SMALL, 1, PRESS_A_TO_EDIT[0] ); 
            }
        } 
        /* Edit Menu Navigation / Adjustable Values */
        if(editMenu){ 
            vm_tctrl(0); 
            tff_power             = editValues(tff_power           ,0 );
            tff_accuracy          = editValues(tff_accuracy        ,1 );
            tff_ping              = editSwitch(tff_ping            ,2 ); // edit switch function 
            tff_single_btn        = editSwitch(tff_single_btn      ,3 ); // edit switch function 
            EA_Ping               = editValues(EA_Ping             ,4 );
            tf_power              = editValues(tf_power            ,5 );
            tf_accuracy           = editValues(tf_accuracy         ,6 );
            tf_ping               = editSwitch(tf_ping             ,7 ); // edit switch function 
            tf_single_btn         = editSwitch(tf_single_btn       ,8 ); // edit switch function 
            t_trivela_power       = editValues(t_trivela_power     ,9 );
            t_trivela_accuracy    = editValues(t_trivela_accuracy  ,10);
            t_trivela_ping        = editSwitch(t_trivela_ping      ,11); // edit switch function 
            t_trivela_single_btn  = editSwitch(t_trivela_single_btn,12); // edit switch function 
            /* Navigate Edit Menu */
            if(!get_ival(PS4_L2)){ 
                if(event_press(PS4_RIGHT)){ 
                    valNameIdx = clamp(valNameIdx + 1,valRangeIdx[modNameIdx][0],valRangeIdx[modNameIdx][1]);
                    updateDisplay = TRUE;
                }
                if(event_press(PS4_LEFT)){ 
                    valNameIdx = clamp(valNameIdx - 1,valRangeIdx[modNameIdx][0],valRangeIdx[modNameIdx][1]);
                    updateDisplay = TRUE;
                }
            }
            /* Exit Edit Menu - Return To Mod Menu */
            if(event_press(PS4_CIRCLE)){ 
                modMenu = TRUE;
                editMenu = FALSE;
                updateDisplay = TRUE;
            }
            
            BlockButtonPress ();
            //==============================================
            // DIsply Edit
            f_min = valuesMinMax[valNameIdx][0];                          
            f_max = valuesMinMax[valNameIdx][1];  
            //---- Edit Value
            if(valuesMinMax[valNameIdx][4] == 0 ) {
                // on the left: min value                                          
                print_number(f_min ,find_digits(f_min) ,4 , 20 , OLED_FONT_SMALL); 
                // on the right: max value                                         
                print_number(f_max ,find_digits(f_max) ,97 , 20 , OLED_FONT_SMALL);
            }
        }
        /* When We are Either In Mod Menu OR Edit Menu - Update/Refresh The Display for the OLED */
        if(updateDisplay){ 
            cls_oled(OLED_BLACK);  // Clear The Screen 
            rect_oled(0, 0, OLED_WIDTH, OLED_HEIGHT, OLED_BLACK, OLED_WHITE);
            line_oled(0,14,127 , 14, 1, 1); 
            /* Display Val Names / Adjustble Values when In Edit Menu */
            if(editMenu){ 
                print(centerPosition(getStringLength(valNames[valNameIdx]) ,OLED_FONT_SMALL_WIDTH), 3  ,OLED_FONT_SMALL  , OLED_WHITE , valNames[valNameIdx]);
                
            }
            /* Display Mod Names / Toggles When In Mod Menu */
            else { 
                print(centerPosition(getStringLength(modNames[modNameIdx]) ,OLED_FONT_SMALL_WIDTH), 3  ,OLED_FONT_SMALL , OLED_WHITE , modNames[modNameIdx]);
            }
            updateDisplay = FALSE; // When No Buttons are Pressed In the menu / Update Display is FALSE 
        }
    } 
    /* When We ARE NOT in ModMenu or EditMenu */
    if(!modMenu && !editMenu){
        /* Display The Title Screen When we Are NOT in any Menu s */
        if(displayTitle){ 
            cls_oled(0);
            DrawLogo(0, 0, 0);
            displayTitle = FALSE;
            screenSaver  = TRUE;
            combo_run(rgb);
            print(centerPosition(getStringLength( AUTHOR[0]) ,OLED_FONT_SMALL_WIDTH), 35  ,OLED_FONT_SMALL , OLED_WHITE , AUTHOR[0]);
            print(centerPosition(getStringLength(VERSION[0]) ,OLED_FONT_SMALL_WIDTH), 48  ,OLED_FONT_SMALL , OLED_WHITE , VERSION[0]);
        }
        /* When We are Display Title , after 10 seconds activate Screen Saver (Blank Screen) To Prevent Screen Burn */
        if(screenSaver){  
            blankScreen += get_rtime();
        
            if(blankScreen >= 10000)
            {
                cls_oled(OLED_BLACK);
                blankScreen = 0;
                screenSaver = FALSE;
            } 
        }
        /* This is where all mods are placed outside the menu */
        /* Add Mods */ 
		    //=======================================================
           if(Get_LS_Output){  
               if(abs(get_val(PS4_LX))> 45 || abs(get_val(PS4_LY))> 45){
                   calc_zone (); 
                   LX = ZONE_P[zone_p][0];
                   LY = ZONE_P[zone_p][1];
               }//======================================================
           }                                                          
            if(get_ival(PS4_R3)){                              
	            if(event_press(XB1_RIGHT)) {
	                EA_Ping +=1;
	                on_the_fly_display(centerPosition(sizeof(EA_PING)- 1,OLED_FONT_MEDIUM_WIDTH),EA_PING[0],EA_Ping);
            	}
            	if(event_press(XB1_LEFT)) {
	                EA_Ping -=1;
	                on_the_fly_display(centerPosition(sizeof(EA_PING)- 1,OLED_FONT_MEDIUM_WIDTH),EA_PING[0],EA_Ping);
                }
            }

                 //===========================================
                 //   TIMED FINISH  
                 //===========================================
                 if(TimedFinish_on_off ) {
                     if(combo_running(TIMED_FINISH_FULL_cmb)) vm_tctrl(0);
                     if(combo_running(TimedFinish_cmb)) vm_tctrl(0);
                     tf_start_btn = SelectBtn[tf_single_btn];
                 	   if(TimedFinish_on_off == 1) {
                         if(get_ival(tf_start_btn)){ 
                             set_val(tf_start_btn,0);
                             combo_run(TIMED_FINISH_FULL_cmb);
                         }
                          set_val(tf_start_btn,0);
                     }
                     if(TimedFinish_on_off == 2) {
                         if(get_ival(ShotBtn) && get_ptime(ShotBtn) > tf_power){ 
                             set_val(ShotBtn,0);
                             combo_run(TimedFinish_cmb);
                         }
                     }
                     else if(TimedFinish_on_off == 3) {
                         if(event_press(ShotBtn)){ 
                             combo_run(TIMED_FINISH_FULL_cmb);    
                         }
                     }
                 }  
                 //===========================================
                 //   TIMED FINESSE FINISH  
                 //===========================================
                 // Single Button start TFF  
                 if(TimedFinesFinish_on_off ) {
                     if(combo_running(TFF_FULL_POWER_cmb)) vm_tctrl(0);
                     if(combo_running(Timed_Finesse_Finishing_cmb)) vm_tctrl(0);
                     tff_start_btn = SelectBtn[tff_single_btn];
                     //1 Timed Finish single btn
                     if(TimedFinesFinish_on_off == 1){
                         if(get_ival(tff_start_btn)  ){ 
                             vm_tctrl(0);                
                             combo_run(TFF_FULL_POWER_cmb); 
                         }                              
                          set_val(tff_start_btn,0);
                     }
                     // Tap to shoot/ Hold = Full Power
                     if(TimedFinesFinish_on_off == 2){
                         if(get_ival(FinesseShot)){ 
                             if(get_ival(ShotBtn) && get_ptime(ShotBtn) > tff_power){ 
                                 set_val(ShotBtn,0);
                                 combo_run(Timed_Finesse_Finishing_cmb);
                             }  
                         }
                     }
                     // Full Power TFF
                     else if(TimedFinesFinish_on_off == 3){
                         if(get_ival(FinesseShot)){ 
                             if(event_press(ShotBtn)){ 
                                 combo_run(TFF_FULL_POWER_cmb);    
                             }  
                         }
                     }
                 }
         
			     //========================================== 
			     // 32. TIMED TRIVELA
			     //==========================================
           //1. Timed Trivela Single Button  
	         if(TimedTrivelaShot_Toggle == 1){
                if(get_ival(SelectBtn[t_trivela_single_btn])  ){ 
                    vm_tctrl(0);                                  
                    combo_run(TTRIVELA_FULL_POWER_cmb);                       
                }                                              
                set_val(SelectBtn[t_trivela_single_btn],0);
            }
          
            //2. Timed Trivela Standard
            if(TimedTrivelaShot_Toggle == 2){
                if( get_ival(PaceCtrol) ){                       
                    if(get_ival(ShotBtn) && get_ptime(ShotBtn)> t_trivela_power ){ 
                        set_val(ShotBtn,0);                            
                        vm_tctrl(0);                                  
                        combo_run(TIMED_TRIVELA_cmb);                       
                    }                                              
                }
            }      
      
            //3. Timed Trivela Full Power 
            if(TimedTrivelaShot_Toggle == 3){
                if( get_ival(PaceCtrol) ){                     
                    if(get_ival(ShotBtn)  ){                       
                        set_val(ShotBtn,0);                       
                        vm_tctrl(0);                                
                        combo_run(TTRIVELA_FULL_POWER_cmb);          
                    }                                             
                } 
            }
    }//!modMenu && !editMenu    
  }// Entire Script ON 
  else LED_Color(Red); 
} // END OF MAIN BLOCK

define Y_pos = 19;
function toggleSwitch(fVar,fIdx){ 
    if(modNameIdx == fIdx){ 
        if(event_press(PS4_RIGHT)){ 
            fVar = clamp(fVar + 1,0,toggleMax[modNameIdx]);  // Max Amount of Toggles From Array
            updateDisplay = TRUE;
        }
        if(event_press(PS4_LEFT)){ 
            fVar = clamp(fVar - 1,0,toggleMax[modNameIdx]); // Max Amount of Toggles From Array
            updateDisplay = TRUE;
        }
        /* Print Strings here... */ 
        if(modNameIdx == 0 ){ 
            print(centerPosition(getStringLength(TimedFinesFinishToggle_Opt[TimedFinesFinish_on_off]) ,OLED_FONT_SMALL_WIDTH ),Y_pos  ,OLED_FONT_SMALL , OLED_WHITE ,TimedFinesFinishToggle_Opt[TimedFinesFinish_on_off]);
        }   
        else if(modNameIdx == 2 ){ 
            print(centerPosition(getStringLength(TimedFinishToggle_Opt[TimedFinish_on_off]) ,OLED_FONT_SMALL_WIDTH ),Y_pos  ,OLED_FONT_SMALL , OLED_WHITE ,TimedFinishToggle_Opt[TimedFinish_on_off]);
        }   
        else if(modNameIdx == 3 ){ 
            print(centerPosition(getStringLength(TrivelaShotToggle_Opt[TimedTrivelaShot_Toggle]) ,OLED_FONT_SMALL_WIDTH ),Y_pos  ,OLED_FONT_SMALL , OLED_WHITE ,TrivelaShotToggle_Opt[TimedTrivelaShot_Toggle]);
        }   
        else { 
            if(fVar == 1)
            print(centerPosition(getStringLength(Toggle[1]),OLED_FONT_SMALL_WIDTH),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Toggle[1])    
        else
            print(centerPosition(getStringLength(Toggle[0]),OLED_FONT_SMALL_WIDTH),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Toggle[0])    
        }
    }
    return fVar; 
} 
//============================================================
function editSwitch(fVar,fIdx){ 
    if(valNameIdx == fIdx){ // Which valNameIdx number we are on \\
        if(get_ival(PS4_L2)){ // Ads 
            if(event_press(PS4_RIGHT)){ 
                fVar += valuesMinMax[valNameIdx][2] // Increase value by desired in Array 
                updateDisplay = TRUE;
            }
            if(event_press(PS4_LEFT)){ 
                fVar -= valuesMinMax[valNameIdx][2] // Increase value by desired in Array 
                updateDisplay = TRUE;
            }
            fVar = clamp(fVar,valuesMinMax[valNameIdx][0],valuesMinMax[valNameIdx][1]);// Min and Max Value
        }
        /*===============================================================================================================================
        Display Toggle Strings 
        =================================================================================================================================
        */
		if(valNameIdx == 3){ 
			print(centerPosition(getStringLength(Select_btn_Opt[tff_single_btn]),OLED_FONT_SMALL_WIDTH ),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Select_btn_Opt[tff_single_btn]) 
		}       
		else if(valNameIdx == 8){ 
			print(centerPosition(getStringLength(Select_btn_Opt[tf_single_btn]),OLED_FONT_SMALL_WIDTH),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Select_btn_Opt[tf_single_btn]) 
		}       
		else if(valNameIdx == 12){ 
			print(centerPosition(getStringLength(Select_btn_Opt[t_trivela_single_btn]),OLED_FONT_SMALL_WIDTH),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Select_btn_Opt[t_trivela_single_btn]) 
		}       
        else { 
            if(fVar == 1)
            print(centerPosition(getStringLength(Toggle[1]),OLED_FONT_SMALL_WIDTH),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Toggle[1])    
        else
            print(centerPosition(getStringLength(Toggle[0]),OLED_FONT_SMALL_WIDTH),Y_pos,OLED_FONT_SMALL,OLED_WHITE,Toggle[0])    
        }
        edit_value_help (0);    
    }
    return fVar;
}
/*
==================================================================================================================
Edit Values Function For Edit Menu 
==================================================================================================================
*/
function editValues(fVar,fIdx){ 
	if(valNameIdx == fIdx){ 
		if(get_ival(PS4_L2)){ // Ads 
			if(event_press(PS4_RIGHT)){ 
				fVar += valuesMinMax[valNameIdx][2] // Increase value by desired in Array 
				updateDisplay = TRUE;
			}
			if(event_press(PS4_LEFT)){ 
				fVar -= valuesMinMax[valNameIdx][2] // Decrease value by desired in Array 
                updateDisplay = TRUE;
            }
            if(event_press(PS4_UP)){ 
                fVar += valuesMinMax[valNameIdx][3] // Increase value by desired in Array 
                updateDisplay = TRUE;
            }
            if(event_press(PS4_DOWN)){ 
                fVar -= valuesMinMax[valNameIdx][3] // Increase value by desired in Array 
                updateDisplay = TRUE;
            }
            fVar = clamp(fVar,valuesMinMax[valNameIdx][0],valuesMinMax[valNameIdx][1]);// Min and Max Value
        }
        NumberToString(fVar,FindDigits(fVar));  // Display Value 
    }
    return fVar;
}
int c_c_c,n_str_,c_val;                                
function print_number(f_val,f_digits ,print_s_x , print_s_y , f_font) { 
                                                      
    n_str_ = 1;  c_val = 10000;                       
                                                      
    if(f_val < 0) //--neg numbers                     
    {                                                 
         putc_oled(n_str_,45);    //--add leading "-" 
         n_str_ += 1;                                 
         f_val = abs(f_val);                          
    }                                                 
    for(c_c_c = 5; c_c_c >= 1; c_c_c--)                           
    {                                                 
        if(f_digits >= c_c_c)                             
        {                                              
            putc_oled(n_str_,ASCII_NUM[f_val / c_val]);
            f_val = f_val % c_val;                    
            n_str_ +=  1;                             
                                                      
        }                                             
        c_val /= 10;                                  
    }                                                 
    puts_oled(print_s_x,print_s_y,f_font,n_str_ - 1,OLED_WHITE); // adjustable value centered in X
} 

const string NO_EDIT_VARIABLE =" No Edit Variable";
const string PRESS_A_TO_EDIT  =" A/CROSS to Edit ";
const string MOD_LABEL        ="MOD:";
const string SLOT_LABEL       ="MSL:";
int slot_numb ;
function find_digits(f_num) {                         
//  find_digits(value)                                
//        return Number of Digits in Value Passed     
                                                      
    f_num = abs(f_num);                               
    if(f_num / 10000 > 0) return 5;                   
    if(f_num /  1000 > 0) return 4;                   
    if(f_num /   100 > 0) return 3;                   
    if(f_num /    10 > 0) return 2;                   
                          return 1;                  
} 
const int8 ASCII_NUM[] =                          
//      0  1  2  3  4  5  6  7  8  9  (column numbers)
      {48,49,50,51,52,53,54,55,56,57};
      
int f_min,f_max;

/*     
======================================================
     Logo Picture : Default ZEN Logo
======================================================
*/                                                    
                               
 const int16 BOOT_LOGO[] = { 
128, 29,
    0x0000,0x0000,0x0000,0x0000,0x0000,0x0007,0xF800,0x3FF0,0x07FF,0xFFCF,0xF1FF,0xFFE0,0x7FE0,0x001F,0xFE00,0x7FF8,0x07FF,0xFFCF,0xF3FF,0xFFE0,0x7FE0,0x007F,0xFF00,0xFFFC,0x0FFF,0xFF8F,0xF3FF,0xFFE0,0xFFE0,0x00FF,0xFF81,0xFFFE,
    0x0FFF,0xFF8F,0xF3FF,0xFFE0,0xFFE0,0x01FF,0xFFC3,0xFFFF,0x0FFF,0xFF9F,0xE3FF,0xFFE1,0xFFE0,0x01FF,0xFFC7,0xFFFF,0x0FFF,0xFF9F,0xE3FF,0xFFE1,0xFFE0,0x03FC,0x3FC7,0xF8FF,0x0FF0,0x001F,0xE7F8,0x0003,0xFFF0,0x03FC,0x3FCF,0xF07F,
    0x0FE0,0x001F,0xE7F8,0x0003,0xFFF0,0x03F8,0x3FCF,0xE07F,0x1FE0,0x001F,0xE7F8,0x0007,0xF7F0,0x03F8,0x3FC0,0x007F,0x1FE0,0x001F,0xC7F8,0x0007,0xE7F0,0x0000,0x3F80,0x00FE,0x1FE0,0x003F,0xC7F8,0x000F,0xE7F0,0x0000,0x7F80,0x01FE,
    0x1FFF,0xF83F,0xCFFF,0xFE0F,0xE7F0,0x0000,0xFF00,0x07FC,0x1FFF,0xF83F,0xCFFF,0xFE1F,0xC7F8,0x0001,0xFE00,0x1FF8,0x3FFF,0xF83F,0xCFFF,0xFE1F,0xC7F8,0x0003,0xFE00,0x1FF0,0x3FFF,0xF83F,0xCFFF,0xFC3F,0x87F8,0x0007,0xFC00,0x1FF8,
    0x3FFF,0xF83F,0x8FFF,0xFC3F,0x83F8,0x000F,0xF800,0x1FFC,0x3FFF,0xF07F,0x8FFF,0xFC7F,0x03F8,0x001F,0xF000,0x07FE,0x3FC0,0x007F,0x9FF0,0x00FF,0xFFF8,0x003F,0xC000,0x03FE,0x3F80,0x007F,0x9FE0,0x00FF,0xFFFC,0x007F,0x8000,0x01FE,
    0x7F80,0x007F,0x9FE0,0x01FF,0xFFFC,0x00FF,0x003F,0x81FE,0x7F80,0x007F,0x9FE0,0x01FF,0xFFFC,0x01FE,0x003F,0x81FE,0x7F80,0x00FF,0x1FE0,0x03FF,0xFFFC,0x03FE,0xFE3F,0x83FC,0x7F80,0x00FF,0x1FC0,0x03FF,0xFFFC,0x07FF,0xFE3F,0xFFFC,
    0x7F80,0x00FF,0x3FC0,0x07F8,0x01FC,0x0FFF,0xFE3F,0xFFF8,0xFF00,0x00FF,0x3FC0,0x07F0,0x01FE,0x1FFF,0xFE3F,0xFFF0,0xFF00,0x00FF,0x3FC0,0x0FF0,0x01FE,0x1FFF,0xFE1F,0xFFE0,0xFF00,0x01FE,0x3FC0,0x0FE0,0x01FE,0x1FFF,0xFE0F,0xFFC0,
    0xFF00,0x01FE,0x3F80,0x1FE0,0x01FE,0x1FFF,0xFC07,0xFF80
 
 } // picture 
/*     
======================================================
     DrawLogo(x, y, invert)                            
====================================================== 
*/                                                    
int logoX,logoX2,logoY, logoY2;                       
int logoBit,logoOffset,logoData;                      
                                                      
function DrawLogo(x, y, invert) {                     
    logoOffset = 2;                                    
    logoBit = 16;                                           
    for (logoY = 0; logoY < BOOT_LOGO[1]; logoY++) {         // Loop the Y axis 
        for (logoX = 0; logoX < BOOT_LOGO[0]; logoX++) {     // Loop the X axis 
            logoData = BOOT_LOGO[logoOffset]          
            logoX2 = x + logoX;                       
            logoY2 = y + logoY;                       
            if (logoX2 < 0 || logoX2 >= 128) {        
                logoX2 -= 128;                        
            }                                         
            if (logoY2 < 0 || logoY2 >= 64) {         
                logoY2 -= 64;                         
            }                                         
            if (test_bit(logoData, logoBit - 1)) {     
                pixel_oled(logoX2, logoY2, !invert);   
            }else{                                     
                pixel_oled(logoX2, logoY2, invert);    
            }                                            
            logoBit--;             // Decrement the bit flag, we are moving to the next bit 
            if (!logoBit) {     // Check if we have just handled the last bit  
                logoBit = 16;     // Reset the bit flag     
                logoOffset++;     // Move to the next value 
            }  
        }   
    }    
}           
int inc = 1, dec, color[3];
combo rgb {
  wait(1);
  set_rgb(color, color[1], color[2]);
  color[dec] -= 1; color[inc] += 1;
  if(!color[dec]) { inc = (inc + 1) % 3; dec = (dec + 1) % 3; }
}
function Refresh(Value,Min,Max){  
    if(Value > Max) 
        return Min;         
    if(Value < Min)
        return Max;     
    return Value;    
}
combo rumbleOn {
set_ledx(2, 2);
set_rumble(RUMBLE_B, 50);
wait(150);
reset_rumble();
wait(100);
set_rumble(RUMBLE_B, 50);
wait(150);
reset_rumble();
reset_leds();
}
combo rumbleOff {                        
set_ledx(1, 1);
set_rumble(RUMBLE_A, 50);
wait(300);
reset_rumble();
wait(400);
reset_leds();
}
int stringLength;
function getStringLength(offset) { 
    stringLength = 0;
    do { 
        offset++;
        stringLength++;
    } while (duint8(offset));
    return stringLength;
 } 
 
int i;
const uint8 BlockButtons [] = {  
  PS4_L2,PS4_OPTIONS,PS4_LEFT, PS4_RIGHT,PS4_UP,PS4_DOWN,PS4_CROSS,PS4_CIRCLE,PS4_SQUARE,PS4_TRIANGLE,PS4_L1,PS4_R1,PS4_R2}; 
function BlockButtonPress (){  
    for(i = 0; i < 13; i++){
        if(get_ival(BlockButtons[i]) || event_press(BlockButtons[i])){
            set_val(BlockButtons[i],0);
        }    
    }
}
define UP_arrow = 131; define DOWN_arrow = 132; define LEFT_arrow = 133; define RIGHT_arrow = 134; define TRIANGLE = 130; define Y = 89; define CROSS = 127; define A = 65;
int col_char_left; 
int col_char_right;
int col_rec_left = 1;
int col_rec_right = 1;
define Y_Arrow = 36;
const string EDIT_VALUE_TXT = "Hold LT/L2 +"; 

function edit_value_help (f_part){
    line_oled(1,48,127,48,1,1); 
    // print text 
    print( 2, 52, OLED_FONT_SMALL, 1, EDIT_VALUE_TXT[0] ); 
    // print Left/ Right arrow
    rect_oled(90, 50, 127, 60, OLED_WHITE , col_rec_left); // rectangle left (line 1)
    //rect_oled(100, 48, OLED_FONT_SMALL_WIDTH + 2, OLED_FONT_SMALL_HEIGHT + 2, OLED_WHITE, col_rec_right); // rectangle right (line 1)
    putc_oled(1,LEFT_arrow); 
    puts_oled(91, 51, OLED_FONT_SMALL, 1, col_char_left);     
    putc_oled(1,RIGHT_arrow); 
    puts_oled(101, 51, OLED_FONT_SMALL, 1, col_char_right);
    
    if(f_part){
    putc_oled(1,UP_arrow); 
    puts_oled(111, 51, OLED_FONT_SMALL, 1, col_char_left);     
    putc_oled(1,DOWN_arrow); 
    puts_oled(121, 51, OLED_FONT_SMALL, 1, col_char_right);
    }
}
function Load() {
      
		TimedFinesFinish_on_off        = get_pvar(SPVAR_1 ,       1,       3,       3); // 1 
		UniversalPingToggle            = get_pvar(SPVAR_2 ,       0,       1,       0); // 2 
		TimedFinish_on_off             = get_pvar(SPVAR_3 ,       1,       3,       2); // 3 
		TimedTrivelaShot_Toggle        = get_pvar(SPVAR_4 ,       0,       3,       0); // 4 
		tff_power                      = get_pvar(SPVAR_5 ,       1,     250,     230); // 5 
		tff_accuracy                   = get_pvar(SPVAR_6 ,       1,     250,     150); // 6 
		tff_ping                       = get_pvar(SPVAR_7 ,       0,       1,       1); // 7 
		tff_single_btn                 = get_pvar(SPVAR_8 ,       1,      21,       0); // 8 
		EA_Ping                        = get_pvar(SPVAR_9 ,       0,     300,       0); // 9 
		tf_power                       = get_pvar(SPVAR_10 ,       1,     250,     220); // 10 
		tf_accuracy                    = get_pvar(SPVAR_11,       1,     250,     160); // 11
		tf_ping                        = get_pvar(SPVAR_12,       0,       1,       1); // 12
		tf_single_btn                  = get_pvar(SPVAR_13,       1,      21,       5); // 13
		t_trivela_power                = get_pvar(SPVAR_14,       1,     600,     245); // 14
		t_trivela_accuracy             = get_pvar(SPVAR_15,       1,     250,     150); // 15
		t_trivela_ping                 = get_pvar(SPVAR_16,       0,       1,       1); // 16
		t_trivela_single_btn           = get_pvar(SPVAR_17,       0,      21,       0); // 17
}
//=========================================================
//  SAVE FUNCTION 
//=========================================================
function Save(){  
	set_pvar(SPVAR_1 ,TimedFinesFinish_on_off); // 1 
	set_pvar(SPVAR_2 ,UniversalPingToggle ); // 2 
	set_pvar(SPVAR_3 ,TimedFinish_on_off  ); // 3 
	set_pvar(SPVAR_4 ,TimedTrivelaShot_Toggle); // 4 
	set_pvar(SPVAR_5 ,tff_power           ); // 5 
	set_pvar(SPVAR_6 ,tff_accuracy        ); // 6 
	set_pvar(SPVAR_7 ,tff_ping            ); // 7 
	set_pvar(SPVAR_8 ,tff_single_btn      ); // 8 
	set_pvar(SPVAR_9 ,EA_Ping             ); // 9 
	set_pvar(SPVAR_10 ,tf_power            ); // 10 
	set_pvar(SPVAR_11,tf_accuracy         ); // 11
	set_pvar(SPVAR_12,tf_ping             ); // 12
	set_pvar(SPVAR_13,tf_single_btn       ); // 13
	set_pvar(SPVAR_14,t_trivela_power     ); // 14
	set_pvar(SPVAR_15,t_trivela_accuracy  ); // 15
	set_pvar(SPVAR_16,t_trivela_ping      ); // 16
	set_pvar(SPVAR_17,t_trivela_single_btn); // 17
    combo_run(EXIT);
}// end of SAVE FUNCTION
const string EXIT_TXT1 = "SETTINGS";  
const string EXIT_TXT2 = "WAS SAVED"; 
combo MESSAGE {       
    wait(20);         
    cls_oled(0);      
    print(15, 2, OLED_FONT_MEDIUM, 1, EXIT_TXT1[0]); 
    print(10, 23, OLED_FONT_MEDIUM, 1, EXIT_TXT2[0]);
    Save();
    exit_wait = 1500;     
}
int exit_wait = 1500;
combo EXIT {     
    wait(exit_wait);     
    cls_oled(0); 
    displayTitle = TRUE;     
}            

//--------------------------------------------------------------   
define UP         = 0;  
define UP_RIGHT   = 1;  
define RIGHT      = 2;  
define DOWN_RIGHT = 3;  
define DOWN       = 4;  
define DOWN_LEFT  = 5;  
define LEFT       = 6;  
define UP_LEFT    = 7;  
int dEnd;
                                               
int ACTIVE;                                     
int SKILL ;  
int LX, LY;          // Direction of Left Stick         
int right_on ;                            
int w_rstick  = 50;                        
int OnOffMods = TRUE;                            
int Sombrero;     
int hold_btn = 200;
int Get_LS_Output = TRUE;
int Trivela_Ping = 0;
combo TTRIVELA_FULL_POWER_cmb { 
    if( t_trivela_ping ) { Trivela_Ping = EA_Ping; }
    else { Trivela_Ping = 0; }
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);  
    wait(t_trivela_power); 
    set_val(PaceCtrol,100);
    set_val(ShotBtn,  0);  
    wait(t_trivela_accuracy + Trivela_Ping);
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);  
    wait(t_trivela_power);
    set_val(PaceCtrol,100);
    set_val(ShotBtn,  0);  
    wait(2000); 
}
combo TIMED_TRIVELA_cmb { 
    
    set_val(PaceCtrol,100);
    set_val(ShotBtn,  0);  
    wait(t_trivela_accuracy + Trivela_Ping);
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);  
    wait(t_trivela_power);
    set_val(PaceCtrol,100);
    set_val(ShotBtn,  0);  
    wait(2000); 
}                      
int EntireScript_On = TRUE;
function f_blinck ( var){  
	if(var){               
		BlinckColor = Green;
	}else{                 
		BlinckColor = Red;    
	}                       
	combo_run(BLINK_NOTIFY); 
}                           
int BlinckColor;                            
combo BLINK_NOTIFY {        
	LED_Color(BlinckColor);   
	wait(300);                 
	LED_Color(ColorOFF);        
	wait(100);                  
	LED_Color(BlinckColor);      
    wait(300);                   
    LED_Color(ColorOFF);          
}                                 
 const string SCRIPT_ONOFF  = "SCRIPT WAS";        
 function display_MOD_status(f_val,f_size,f_label){  
    if(!modMenu && !editMenu){                                           
        // Clear OLED Screen                          
        cls_oled(0); // will clear oled   
        print(f_size, 3, OLED_FONT_MEDIUM ,OLED_WHITE, f_label);   
        if( f_val ){
            print(center_x(sizeof(ON)  - 1, OLED_FONT_LARGE_WIDTH),37,OLED_FONT_LARGE,OLED_WHITE, ON[0]);//MOD is ON
        }
        else{
            print(center_x(sizeof(OFF)  - 1, OLED_FONT_LARGE_WIDTH),37,OLED_FONT_LARGE,OLED_WHITE, OFF[0]);// MOD is OFF
        }    
        time_to_clear_screen = 1500;
        f_blinck(f_val);
    } 
}
//=============================================== 
//                 VIBRATE SETUP                 
//=============================================== 
combo vibrate {                                   
    set_rumble(rumble_tipe, 100);                   
    wait(300);                                       
    reset_rumble();                                 
    wait(100);                                       
    set_rumble(rumble_tipe, 100);                   
    wait(300);                                       
    reset_rumble();                                 
}                                                 
//===============================================  
//                 RUMBLE_TIPE                     
//===============================================  
function set_rumble_tipe ( f_val) {                  
    if( f_val){ rumble_tipe = RUMBLE_A ; LED_OnOff = Green;}  
    else      { rumble_tipe = RUMBLE_B ; LED_OnOff = Red  ;} 
    combo_run(vibrate);                     
    combo_run(LED_BLINK);                   
}                          
//=============================================== 
//            LED BLINK                           
//===============================================
int LED_OnOff;       
int rumble_tipe = RUMBLE_A;
combo LED_BLINK {                                 
    LED_Color(LED_OnOff);                           
    wait(200);                                      
    LED_Color(ColorOFF);                            
    wait(100);                                      
    LED_Color(LED_OnOff);                           
    wait(200);                                      
    LED_Color(ColorOFF);                             
    wait(100);                                      
}   
int time_to_clear_screen = 3000;
function center_x(f_chars,f_font) {                                                                 
    return (OLED_WIDTH / 2) - ((f_chars * f_font) / 2); 
} 
const string OFF   = "OFF";       
const string ON    = "ON";

   //=======================================
   //  DISPLAY EDIT VALUE ON THE FLY        
   //=======================================
function on_the_fly_display (f_string, f_print, f_val){
    cls_oled(0);  
    line_oled(1,18,127,18,1,1);
    print(f_string, 0, OLED_FONT_MEDIUM, OLED_WHITE, f_print);  
    NumberToString(f_val, FindDigits(f_val));
    time_to_clear_screen  = 2000;
} 
const string EA_PING = "EA PING";   
   
   
/*   
=================================================================
 Center X Function (Made By Batts) 
=================================================================
*/
function centerPosition(f_chars,f_font) {
    return (OLED_WIDTH / 2) - ((f_chars * f_font) / 2);
}
/*
=================================================================
  NumberToString () (Made By Batts)                                                                                                                     
=================================================================
*/   
int bufferIndex;
int charIndex,digitIndex;
function NumberToString(f_val,f_digits) {
    bufferIndex = 1;  
    digitIndex = 10000;
    if(f_val < 0) {                    //--neg numbers
         putc_oled(bufferIndex,45);    //--add leading "-"
         bufferIndex += 1;
         f_val = abs(f_val);
    } 
    for(charIndex = 5; charIndex >= 1; charIndex--) {
        if(f_digits >= charIndex) {
            putc_oled(bufferIndex,(f_val / digitIndex) + 48);
            f_val %= digitIndex;
            bufferIndex ++; 
            if(charIndex == 4) {
                putc_oled(bufferIndex,44);//--add ","
                bufferIndex ++;
            }
        }
        digitIndex /= 10;
    } 
    puts_oled(centerPosition(bufferIndex - 1,OLED_FONT_MEDIUM_WIDTH),38,OLED_FONT_MEDIUM,bufferIndex - 1,OLED_WHITE);
} 
int logVal;
function FindDigits(num) {
   logVal = 0;
   do {
      num /= 10;
      logVal++;
   } while (num);
   return logVal;
}
combo CLEAR_SCREEN {     
    wait(20);     
    cls_oled(0); 
}            

int OnOFF_Skills;
int ModifierBtn;
int dubltime;
define ColorOFF  = 0;
define Blue      = 1;
define Red       = 2;
define Green     = 3;
define Pink      = 4;
define SkyBlue   = 5;
define Yellow    = 6;
define White     = 7;
                      
data(                 
  0,0,0, //0. ColorOFF
  2,0,0, //1. Blue     
  0,2,0, //2. Red      
  0,0,2, //3. Green    
  2,2,0, //4. Pink     
  2,0,2, //5. SkyBlue 
  0,2,2, //6. Yellow   
  2,2,2  //7. White    
); // end of data segment-------------- 
// COLOR LED function        
//-------------------------------------------------------------- 
                                       
int data_indx;
function LED_Color(color) {  
    for( data_indx = 0; data_indx < 3; data_indx++ ) {
        set_led(data_indx,duint8 ((color * 3) + data_indx));
    }
}

const int8 SelectBtn [] ={
XB1_XBOX, // 0 
XB1_VIEW, // 1 
XB1_MENU, // 2 
XB1_RB,   // 3 
XB1_RT,   // 4 
XB1_RS,   // 5 
XB1_LB,   // 6 
XB1_LT,   // 7 
XB1_LS,   // 8 
XB1_UP,   // 9 
XB1_DOWN, // 10  
XB1_LEFT, // 11  
XB1_RIGHT,// 12  
XB1_Y,    // 13 
XB1_B,    // 14 
XB1_A,    // 15 
XB1_X,    // 16 
XB1_PR1,  // 17 
XB1_PR2,  // 18 
XB1_PL1,  // 19 
XB1_PL2,  // 20 
PS4_TOUCH // 21  
}

int ShootPower;
int TimedFinish_Ping = 0;
int tf_start_btn;
int QT_TimedFinish = TRUE;
combo TIMED_FINISH_FULL_cmb { 
    if(tf_ping ){ TimedFinish_Ping = EA_Ping; }
    else { TimedFinish_Ping = 0; }
    INSIDE_BOX_AIM(39,100);
    set_val(ShotBtn,100);  
    wait(tf_power ); 
    LA(AIM_X,AIM_Y);
    set_val(ShotBtn,  0);  
    wait(tf_accuracy + TimedFinish_Ping);
    LA(AIM_X,AIM_Y);
    set_val(ShotBtn,100);  
    wait(tf_power);
    LA(AIM_X,AIM_Y);
    set_val(ShotBtn,  0);  
    wait(2000); 
} 
combo TimedFinish_cmb { 
    if(tf_ping ){ TimedFinish_Ping = EA_Ping; }
    else { TimedFinish_Ping = 0; }
    set_val(ShotBtn, 0);             
    wait(tf_accuracy + TimedFinish_Ping );       
    set_val(ShotBtn, 100);            
    wait(tf_power);  
    set_val(ShotBtn, 0);              
    wait(1000);                      
}     

int TFF_Ping = 0;
int tff_start_btn;					
combo TFF_FULL_POWER_cmb { 
    if( tff_ping ){ TFF_Ping = EA_Ping; }
    else { TFF_Ping = 0; }
    set_val(FinesseShot,100);  
    set_val(ShotBtn,100);  
    wait(tff_power); 
    set_val(FinesseShot,100);  
    set_val(ShotBtn,  0);  
    wait(tff_accuracy + TFF_Ping);
    set_val(FinesseShot,100);  
    set_val(ShotBtn,100);  
    wait(tff_power);
    set_val(FinesseShot,100);  
    set_val(ShotBtn,  0);  
    wait(2000); 
}
combo Timed_Finesse_Finishing_cmb { 
    if( tff_ping ){ TFF_Ping = EA_Ping; }
    else { TFF_Ping = 0; }
    set_val(FinesseShot,100);  
    set_val(ShotBtn,  0);  
    wait(tff_accuracy + TFF_Ping);
    set_val(FinesseShot,100);  
    set_val(ShotBtn,100);  
    wait(tff_power);
    set_val(FinesseShot,100);  
    set_val(ShotBtn,  0);  
    wait(2000); 
}                      
function FINESSE_CORNER() {
    sensitivity(PS4_LX, 10 , 25);   
    sensitivity(PS4_LY, 10 , 200); 
}
int AIM_X;
int AIM_Y;
function INSIDE_BOX_AIM(f_LX, f_LY) {     
 if(get_ival(PS4_LX) >= 12) AIM_X = f_LX ; 
 else if(get_ival(PS4_LX) <= -12)  AIM_X = inv(f_LX) ;  
               
 if(get_ival(PS4_LY) >= 12) AIM_Y = f_LY ;  
 else if(get_ival( PS4_LY) <= -12) AIM_Y = inv(f_LY);
}  
int RumblePower = 100;
int Vibrate_type;
combo NOTIFY_cmb {
    set_rumble(Vibrate_type,100);
    wait(300);
    reset_rumble();
    wait(20);
}

function f_set_notify (f_val){
    if(f_val)Vibrate_type = RUMBLE_A;
    else     Vibrate_type = RUMBLE_B;
    combo_run(NOTIFY_cmb);
}
function set_right_or_left () {
    right_on = FALSE; 
    if (zone_p == 4 || zone_p == 3 || zone_p == 7 ) { 
        right_on = TRUE; 
    } /// 
}
int time_to_dblclick = 300
int tap;
combo ONE_TAP {                                    
    tap = TRUE;                                    
    wait(time_to_dblclick); // wait for second tap 
    tap = FALSE;                                  
}                                              
int start;
combo DRIBBLING_SKILL_cmb {               
    set_val(FinesseShot,100); 
    wait(20);
    set_val(FinesseShot,100);       
    LA_L_R();
    wait(375);
    wait(20);
    set_val(FinesseShot, 0);
    set_val(SprintBtn,100);  
    wait(800);
    start = FALSE;
    Get_LS_Output = TRUE;
}           
combo BOOSTED_STEPOVER  {
	if (right_on) dEnd = zone_p + 1;
    else dEnd = zone_p - 1;
	calc_relative_xy(dEnd);
	RA_UP ();
	wait(w_rstick);	
	RA_L_R();
	LA (move_lx,move_ly);
	wait(w_rstick);	
	LA (move_lx,move_ly);
	wait(1000);
    Get_LS_Output = TRUE;
}

combo FOUR_TOUCH_TURN_cmb {
    set_val(PaceCtrol,100);
    RA_DOWN ();    // down                  
    wait(w_rstick);
    set_val(PaceCtrol,100);
    wait(30);
    set_val(PaceCtrol,100);
    RA_DOWN ();    // down                  
    wait(w_rstick);     
    Get_LS_Output = TRUE;
}

combo SKILLED_BRIDGE_cmb {
    set_val(PaceCtrol,100);
    RA_UP();
    wait(w_rstick);
    set_val(PaceCtrol,100);
    RA_ZERO();
    wait(w_rstick);
    set_val(PaceCtrol,100);
    RA_DOWN();
    wait(w_rstick);
    Get_LS_Output = TRUE;
}

combo SCOOP_TURN_FAKE {
    RA_L_R () ;
    wait(280);
    LA_L_R()
    set_val(ShotBtn,100); 
    set_val(PaceCtrol,100);
    wait(40); 
    LA_L_R()
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);
    set_val(PassBtn,100); 
    wait(60);
    LA_L_R()
    set_val(PaceCtrol,100);
    set_val(ShotBtn,0);
    set_val(PassBtn,100);
    wait(60);
    wait(250);
    LA_L_R()
    wait(300); 
    Get_LS_Output = TRUE;
}        
                                                                
///////////////////////////////////////////////////////////////////
// 1. Fake Shot           ////////////////////////////////////////
///////////////////////////////////////////////////////////////////
combo FAKE_SHOT {        
	set_val(ShotBtn,100);  
	wait(40);              
	set_val(ShotBtn,100);  
	set_val(PassBtn,100); 
	wait(60);             
	set_val(ShotBtn,0);  
	set_val(PassBtn,100);
	wait(60);           
    Get_LS_Output = TRUE;
}                  
                                                                
///////////////////////////////////////////////////////////////////
// 2.  Heel to Heel ///////////////////////////////////////////////
///////////////////////////////////////////////////////////////////
combo HEELtoHEEL {                        
	RA_UP();       // up                     
	wait(w_rstick);                          
	RA_ZERO ();    // ZERO                   
	wait(w_rstick);                          
	RA_DOWN ();    // down                  
	wait(w_rstick);                         
    Get_LS_Output = TRUE;
}                                        
                                         
                                                                
///////////////////////////////////////////////////////////////////
// 3. RAINBOW   //////////////////////////////////////////////////
///////////////////////////////////////////////////////////////////
combo RAINBOW {          
	RA_DOWN ();    // down 
	wait(w_rstick);        
	RA_UP();       // up   
	wait(w_rstick);        
    Get_LS_Output = TRUE;
}                       
                        
combo DRAG_BACK {            
	set_val(MOVE_X,inv(LX));    
	set_val(MOVE_Y,inv(LY));   
 set_val(FinesseShot,100);  
 set_val(PlayerRun,100);  
	wait(60);                  
	set_val(MOVE_X,inv(LX));    
	set_val(MOVE_Y,inv(LY));   
 set_val(FinesseShot,100);  
 set_val(PlayerRun,100);  
	if(Sombrero) set_val(PS4_R3,100);
	wait(40);                  
    Get_LS_Output = TRUE;
}                            
                                                                
//////////////////////////////////////////////////////////////
// 2. STEP OVER  /////////////////////////////////////////////
//////////////////////////////////////////////////////////////
combo STEP_OVER_FEINT {      
    RA_UP ();         // up   
	wait(w_rstick);             
	RA_L_R ();       // <-/->   
	wait(w_rstick);             
    Get_LS_Output = TRUE;
}                            
/////////////////////////////// 
// Drag to Drag       
combo DRAG_TO_DRAG {    
	LA(0,0);             
	set_val(PaceCtrol,100);
	wait(40);            
	LA(0,0);             
	set_val(PaceCtrol,100);
	set_val(ShotBtn,100);
	wait(40);            
	LA(0,0);             
	set_val(PaceCtrol,100);
	set_val(ShotBtn,100);
	set_val(PassBtn,100);
	wait(80);            
	LA(0,0);             
	set_val(PaceCtrol,100);
	set_val(ShotBtn,0);  
	set_val(PassBtn,100);
	wait(60);            
    Get_LS_Output = TRUE;
}                     
combo HOCUS_POCUS {     
	RA_DOWN (); // Down    
	wait(w_rstick);        
	right_on = FALSE;      
	RA_L_R () ;    // L    
	wait(w_rstick);        
	RA_DOWN ();    // down 
	wait(w_rstick);        
	right_on = TRUE;      
	RA_L_R () ;    // R    
	wait(w_rstick);        
    Get_LS_Output = TRUE;
}                      
combo TRIPLE_ELASTICO { 
	RA_DOWN ();      // Down 
	wait(w_rstick);         
	right_on = TRUE;      
	RA_L_R () ;    // R  
	wait(w_rstick);       
	RA_DOWN ();    // down 
	wait(w_rstick);       
	right_on = FALSE;     
	RA_L_R () ;    // L   
	wait(w_rstick);      
    Get_LS_Output = TRUE;
}                    
combo ELASTICO  {  
	right_on = TRUE;   
	RA_L_R () ;    // R 
	wait(w_rstick);      
	RA_DOWN ();    // down
	wait(w_rstick);      
	right_on = FALSE;    
	RA_L_R () ;    // L 
	wait(w_rstick);     
    Get_LS_Output = TRUE;
}                   
combo REVERSE_ELASTICO  {  
	right_on = FALSE;   
	RA_L_R () ;    // R  
	wait(w_rstick);      
	RA_DOWN ();    // down
	wait(w_rstick);     
	right_on = TRUE;   
	RA_L_R () ;    // L 
	wait(w_rstick);   
    Get_LS_Output = TRUE;
}                  
combo ELASTICO_SHOP_cmb  {  
	set_val(FinesseShot,100);   
	RA_L_R () ;    // R  
	wait(w_rstick);      
	set_val(FinesseShot,100);   
	RA_DOWN ();    // down
	wait(w_rstick);     
	right_on = !right_on;   
	set_val(FinesseShot,100);   
	RA_L_R () ;    // L 
	wait(w_rstick);   
    Get_LS_Output = TRUE;
}                  
combo BAL_ROLL_CUT_180_cmb  {  
	set_val(PlayerRun,100);   
	RA_DOWN ();    // down
	wait(w_rstick);      
	set_val(PlayerRun,100);   
	RA_ZERO ();    // zero
	wait(w_rstick);      
	set_val(PlayerRun,100);   
	RA_DOWN ();    // down
	wait(w_rstick);     
    Get_LS_Output = TRUE;
}                  
///////////////////////////////
// 1. Cruyff Turn      
combo CRUYFF_TURN {    
	set_val(ShotBtn,100); 
	wait(40);             
	LA (inv(LX),inv(LY)); 
	set_val(ShotBtn,100); 
	set_val(PassBtn,100); 
	wait(80);             
	LA (inv(LX),inv(LY)); 
	set_val(ShotBtn,0);   
	set_val(PassBtn,100); 
	wait(60);             
    Get_LS_Output = TRUE;
}                      
combo LA_CROQUETA {        
  set_val(PlayerRun,100);  
  RA_L_R ();      // <-/-> 
  wait(500);//            
    Get_LS_Output = TRUE;
}                         
combo ROULETTE {         
	RA_DOWN ();     // down 
	wait(w_rstick);         
	RA_L_R ();      // <-/->
	wait(w_rstick);         
	RA_UP ();       // up   
	wait(w_rstick);         
    Get_LS_Output = TRUE;
}                        
///////////////////////////////
// Ball Roll                   
combo BALL_ROLL {               
    RA_L_R () ;    // Left or Right 
    set_val(SprintBtn,0);
    sensitivity(PS4_LX, 50, 40);
    sensitivity(PS4_LY, 60, 40);
    wait(310); 
    sensitivity(PS4_LX, 50, 150);
    wait(100);     
    Get_LS_Output = TRUE;
}          
//////////////////////////////////////////////////////   
// 20. Berba / Mcgeady Spin  / 21. Bolasie Flick + R1 / 32 Ball Roll Fake Turn L2 + Berba Spin 
combo TURN_AND_SPIN {  
  if(ACTIVE == BALL_ROLL_FAKE_TURN ) hold_btn = 200;//  Ball Roll Fake Turn L2 
	else hold_btn = 1;      
 wait(hold_btn);
	RA_UP ();      // up   
	wait(w_rstick);         
	RA_ZERO ();    // ZERO  
	wait(w_rstick);          
	RA_L_R () ;    // Left or Right 
	wait(w_rstick);    
    Get_LS_Output = TRUE;
}                   
////////////////////////////////////
//  Tornado Spin + L1    
combo TORNADO_SPIN {     
	RA_DOWN ();    // down  
	wait(w_rstick);         
	RA_ZERO ();    // ZERO  
	wait(w_rstick);         
	RA_L_R ();     //  <-/-> 
	wait(w_rstick);       
    Get_LS_Output = TRUE;
}                     
/////////////////////////////// 
//25.  Ball Roll Chop           
combo BALL_ROLL_CHOP {         
	RA_L_R () ;    // Left or Right 
	wait(300);                     
	RA_ZERO ();    // ZERO         
	wait(w_rstick);                
	RA_OPP () ;    // Left or Right
	wait(300);                    
    Get_LS_Output = TRUE;
}                             
combo FEINT_EXIT {             
	RA_OPP ();                    
	wait(w_rstick);               
	RA_DOWN (); // down           
	wait(w_rstick);               
	RA_L_R ();  //  <-/->         
	wait(w_rstick);               
    Get_LS_Output = TRUE;
}                            
////////////////////////////////////////////////////////////// 
//28. LATERAL HEEL to HEEL /////////////////////////////////// 
////////////////////////////////////////////////////////////// 
// + L1   PlayerRun                  
combo LATERAL_HEELtoHEEL {  
    set_val(PlayerRun,100);
    RA_OPP () ;            
    wait(60);//            
    set_val(PlayerRun,100);
    RA_ZERO ();            
    wait(60);//            
    set_val(PlayerRun,100);
    RA_L_R () ;            
    wait(60);//           
    wait(300);            
    Get_LS_Output = TRUE;
}                         
combo WAKA_WAKA {      
	RA_OPP();  // L       
	wait(w_rstick);       
	LA (0,0);             
	RA_UP();       // up  
	wait(w_rstick);       
                       
	LA (0,0);             
	RA_L_R()     // L     
	wait(w_rstick);       
	right_on = !right_on; 
	LA_L_R();             
	wait(1000);           
    Get_LS_Output = TRUE;
}                      
                       
combo BODY_FEINT  {  
	RA_L_R () ;    // R 
	wait(100);      
 RA_ZERO ();     
	wait(80);      
	LA_L_R();       
	wait(600);      
	wait(600);      
    Get_LS_Output = TRUE;
}                
combo FEINT_FORWARD {
 LA (0,0);           
	wait(w_rstick);     
 LA (0,0);           
	RA_DOWN (); // down 
	wait(w_rstick);     
 LA (0,0);           
	RA_ZERO (); // ZERO 
	wait(w_rstick);     
 LA (0,0);          
	RA_DOWN (); // down 
	wait(w_rstick);    
    Get_LS_Output = TRUE;
}                   
combo  TURN_BACK  {       
	set_val(FinesseShot,100);
	set_val(PlayerRun,100);  
	RA_DOWN ();             
	wait(80);             
    Get_LS_Output = TRUE;
}                  
combo ADVANCED_CROQUETA { 
  set_val(PlayerRun,100); 
  RA_L_R ();      // <-/->
  wait(300);//            
    set_val(PS4_L2,100);     
    set_val(PS4_R2,100);     
  LA_L_R();               
  wait(800);// 800        
    Get_LS_Output = TRUE;
}                         
combo CANCELED_THREE_TOUCH_ROULETTE { 
    RA_DOWN ();    // down       
    wait(w_rstick);              
    RA_ZERO ();    // ZERO      
    wait(w_rstick);             
    RA_L_R ();     //  <-/->    
    wait(w_rstick);             
    set_val(PS4_L2,100);     
    set_val(PS4_R2,100);     
    //LA_L_R();                 
    wait(300);// 800            
    Get_LS_Output = TRUE;
}                              
                                                                
//////////////////////////////////////////////////////////////
// 37. REVERSE STEP OVER  ///////////////////////////
//////////////////////////////////////////////////////////////
combo REVERSE_STEP_OVER {      
	RA_L_R ();       // <-/->   
	wait(w_rstick);             
     RA_UP ();         // up   
	wait(w_rstick);             
    Get_LS_Output = TRUE;
}                            
combo FAKE_DRAG_BACK {   
   LA (inv(LX),inv(LY)); 
   wait(200); //350  
   right_on = FALSE;
   LA_L_R ();            
   wait(50);   //120         
   right_on = !right_on; 
   LA_L_R ();            
   wait(540);           
    Get_LS_Output = TRUE;
}   

combo RAINBOW_TO_SCORPION {          
	RA_DOWN ();    // down 
	wait(40);
	RA_UP(); // up 
	wait(190);//200
	set_val(PaceCtrol,100);// L2
	wait(30);
	set_val(PaceCtrol,100);// L2
	set_val(ShotBtn,100);  // Shoot
	wait(180);        	   
    Get_LS_Output = TRUE;
}                       
combo CANCEL_SHOOT {
     set_val(ShotBtn,100);
     wait(290);
     set_val(PS4_L2,100);
     set_val(PS4_R2,100);
     wait(300);
    Get_LS_Output = TRUE;
}
combo NUTMEG_SKILL {
	set_val(FinesseShot,100);
	set_val(PlayerRun,100);
	wait(20);
	set_val(FinesseShot,100);
	set_val(PlayerRun,100);
	if (right_on) dEnd = zone_p + 1;
    else { 
    	dEnd = zone_p - 1;
		if(dEnd < 0 ) dEnd = 7;
	}
	calc_relative_xy(dEnd);
    RA (move_lx,move_ly);
    set_val(SprintBtn,100);
	wait(100);    
    Get_LS_Output = TRUE;
}
combo CANCELED_TURN_AND_SPIN {  
    RA_UP ();      // up   
    wait(w_rstick);         
    RA_ZERO ();    // ZERO  
    wait(w_rstick);          
    RA_L_R () ;    // Left or Right 
    wait(w_rstick);
    if( ACTIVE == CANCELED_BERBA_SPIN_WITH_DIRECTION) LA_L_R();
    set_val(PS4_L2,100);
    set_val(PS4_R2,100);
    wait(200);
    if( ACTIVE == CANCELED_BERBA_SPIN_WITH_DIRECTION) LA_L_R();
    wait(300);
    Get_LS_Output = TRUE;
}    
combo BALL_ROLL_SCOOP_TURN {
    RA_L_R () ;
    wait(280);
    LA_L_R()
    set_val(ShotBtn,100); 
    set_val(PaceCtrol,100);
    wait(40); 
    LA_L_R()
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);
    set_val(PassBtn,100); 
    wait(60);
    LA_L_R()
    set_val(PaceCtrol,100);
    set_val(ShotBtn,0);
    set_val(PassBtn,100);
    wait(60);
    Get_LS_Output = TRUE;
}        
combo BALL_ROLL_STEP_OVER_cmb { 
	RA_L_R (); //  <-/->  
	wait(300);    
	RA_UP();      
	wait(60);   
    Get_LS_Output = TRUE;
}          
combo CANCEL_FOUR_TOUCH_TURN_cmb {
    set_val(PaceCtrol,100);
    RA_DOWN ();    // down  
    wait(w_rstick);
    set_val(PaceCtrol,100);
    wait(30);
    set_val(PaceCtrol,100);
    RA_DOWN ();    // down 
    wait(w_rstick);
    LA(0,0);
    wait(400);
    set_val(PS4_L2,100);
    set_val(PS4_L1,100);
    set_val(PS4_R1,100);
    set_val(PS4_R2,100);
    wait(70);      
    Get_LS_Output = TRUE;
}
combo FAKE_SHOT_CANCEL_cmb {        
    set_val(ShotBtn,100);  
    wait(40);              
    set_val(ShotBtn,100);  
    set_val(PassBtn,100); 
    wait(60);             
    set_val(ShotBtn,0);  
    set_val(PassBtn,100);
    wait(60);
    wait(140);
    set_val(PS4_L2,100);
    set_val(PS4_R2,100);
    wait(100);
    Get_LS_Output = TRUE;
}                  

combo OKKOSHA_FLICK_cmb {        
  set_val(PlayerRun,100);
  RA_UP ();      // <-/-> 
  wait(300);//            
    Get_LS_Output = TRUE;
} 
combo ADVANCED_RAINBOW_cmb { 
    LA(LX,LY);
	RA_DOWN ();    // down 
	wait(100); 
	RA_ZERO();     // Zero 
	LA(LX,LY);
	wait(40);
	RA_UP(); 
	LA(LX,LY);      // up   
	wait(320); 
	LA(LX,LY);
	RA_ZERO();     // Zero   
	wait(220); 
	LA(LX,LY);
	RA_UP(); 
    LA(LX,LY);       // up   
    wait(100);
    Get_LS_Output = TRUE;
} 

combo STOP_LA_CROQUETA_cmb {
  LS_BlockOutput = TRUE;
  call(STOP_PLAYER_cmb);
  call(LA_CROQUETA);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}

combo JUGGLING_RAINBOW_cmb {
  LS_BlockOutput = TRUE;
  call(STOP_PLAYER_cmb);
  wait(60);
  call(JUGGLING_cmb);
  call(JUGGLING_cmb);
  call(JUGGLING_cmb);
  call(JUGGLING_cmb);
  call(JUGGLING_cmb);
  set_val(PaceCtrol,100);
  RA_DOWN ();    // down 
  wait(70);      
  set_val(PaceCtrol,100);
  RA_ZERO();     // Zero 
  wait(40);
  set_val(PaceCtrol,100);
  RA_UP();        // up   
  wait(70);
  set_val(PaceCtrol,100);
  wait(800);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}
combo STOP_NEYMAR_ROLL_cmb {
  LS_BlockOutput = TRUE;
  call(STOP_PLAYER_cmb);
  RA_L_R();
  wait(200);
  RA_L_R();
  LA(LX,LY);
  wait(125);
  wait(300);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}
combo STOP_V_DRAG_cmb {
LS_BlockOutput = TRUE;
    call(STOP_PLAYER_cmb);
    set_val(SprintBtn,100);
    wait(125);
    set_val(ShotBtn,100); 
    set_val(SprintBtn,100);
    wait(30); 
    LA_L_R();
    set_val(SprintBtn,100);
    set_val(ShotBtn,100);
    set_val(PassBtn,100); 
    wait(30);
    LA_L_R();
    set_val(SprintBtn,100);
    set_val(ShotBtn,0);
    set_val(PassBtn,100);
    wait(30);
    LA_L_R();
    wait(400);
    LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}

combo REV_OR_ELASTICO_cmb {
  LS_BlockOutput = TRUE;
  RA_OPP (); // down  
  wait(w_rstick);  
  RA_DOWN (); // down  
  wait(w_rstick);
  RA_L_R ();  //  <-/->   
  wait(w_rstick); 
  wait(300);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}
combo STOP_REV_OR_ELASTICO_cmb {
  LS_BlockOutput = TRUE;
  call(STOP_PLAYER_cmb);
  call(FEINT_EXIT);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}

combo DRAG_REV_OR_ELASTICO_cmb {
  LS_BlockOutput = TRUE;
  zone_saver();
  call(DRAG_BACK);
  wait(280);
  RA_OPP ();                    
  wait(w_rstick);               
  RA_DOWN (); // down  
  wait(w_rstick);               
  RA_L_R ();  //  <-/->   
  wait(w_rstick); 
  wait(300);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}

combo FAKE_RABONA_cmb{
    LA(inv(LX),inv(LY));
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);  
    wait(40);
    LA(inv(LX),inv(LY));
    set_val(PaceCtrol,100);
    set_val(ShotBtn,100);  
    set_val(PassBtn,100); 
    wait(60);
    LA(inv(LX),inv(LY));
    set_val(PaceCtrol,100);
    set_val(ShotBtn,0);  
    set_val(PassBtn,100);
    wait(60);
    LA(0,0);
    wait(300);
    Get_LS_Output = TRUE;
}

combo RABONA_TO_REV_ELASTICO_cmb {
  LS_BlockOutput = TRUE;
  zone_saver(); 
  call(FAKE_RABONA_cmb);
  wait(100);
  // NOW player is at zone_p+2 ( example : if he was running up , after fake rabona he face right ).
  // now I will perform reverse - elastico  manually to fit face right .
  // LX,LY values still for running (UP) ,, so we will make the rotation for RA Functions instead of using +2 zone_p method.
  //1//
  RA_UP();   // original elastico is (RA_OPP())
  wait(w_rstick); 
  //2//
  right_on = FALSE; //ALWAYS to player back which is left direction in our case (REV-ELASTico) // original elastico is (RA_DOWN())
  RA_L_R ();
  wait(w_rstick);    
  //3//
  RA_DOWN ()  // original elastico is (RA_L_R())
  wait(w_rstick); 
  wait(400);
  //RA functions rotation done
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}

combo RABONA_TO_ELASTICO_cmb {
  LS_BlockOutput = TRUE;
  zone_saver(); 
  call(FAKE_RABONA_cmb);
  wait(100);
  // NOW player is at zone_p+2 ( example : if he was running up , after fake rabona he face right ).
  // now I will perform reverse - elastico  manually to fit face right .
  // LX,LY values still for running (UP) ,, so we will make the rotation for RA Functions instead of using +2 zone_p method.
  //1//
  RA_DOWN();       // original elastico is (RA_OPP())                
  wait(w_rstick); 
  //2//
  right_on = FALSE; //ALWAYS to player back which is left direction in our case (REV-ELASTico) // original elastico is (RA_DOWN())
  RA_L_R ();
  wait(w_rstick);    
  //3//
  RA_UP ()    // original elastico is (RA_L_R())
  wait(w_rstick); 
  wait(400); 
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}
combo SOMBRERO_FLICK_cmb {
LS_BlockOutput = TRUE;
    call(STOP_PLAYER_cmb);
    wait(100);
    RA_UP();
    wait(50);
    RA_ZERO ()
    wait(50);
    RA_UP()
    wait(50);
    RA_ZERO ()
    wait(50);
    RA_DOWN(); 
    wait(50);
    wait(700);
    LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}
combo JUGGLE_BACK_SOMBRERO_cmb {
  LS_BlockOutput = TRUE;
  call(STOP_PLAYER_cmb);
  wait(100);
  call(JUGGLING_cmb);
  call(JUGGLING_cmb);
  set_val(PaceCtrol,100);
  set_val(FinesseShot,100);
  LA(inv(LX),inv(LY));
  wait(400);
  LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
}

combo FAKE_BARBA_OPP_EXIT_cmb{
	LA(LX,LY);
	RA_UP();
	wait(w_rstick);
	LA(LX,LY);
	RA_ZERO();
	wait(w_rstick);
	LA(LX,LY);
	RA_L_R();
	wait(w_rstick);
	set_val(PaceCtrol,100);
	set_val(SprintBtn,100);
	LA(inv(LX),inv(LY));
	wait(600);
    Get_LS_Output = TRUE;
}
combo DIAGONAL_HEEL_CHOP_cmb {

    if(right_on) dEnd = zone_p + 3;
    else dEnd = zone_p - 3;
    calc_relative_xy(dEnd);
    LA (move_lx,move_ly);
    set_val(ShotBtn,100); 
    wait(40);             
    LA (move_lx,move_ly); 
    set_val(ShotBtn,100); 
    set_val(PassBtn,100); 
    wait(80);             
    LA (move_lx,move_ly);
    set_val(ShotBtn,0);   
    set_val(PassBtn,100); 
    wait(60); 
    LA (move_lx,move_ly);
    wait(300);
    Get_LS_Output = TRUE;
}             
combo FAKE_BARBA_TO_FAKE_DRAG_cmb{
    LA(LX,LY);
    LS_BlockOutput = TRUE;
    set_val(XB1_LS,100);
    RA_UP();
    wait(w_rstick);
    LA(LX,LY);
    RA_ZERO();
    set_val(XB1_LS,100);
    wait(w_rstick);
    LA(LX,LY);
    RA_L_R();
    wait(w_rstick);
    set_val(PaceCtrol,100);
    set_val(SprintBtn,100);
    if(right_on) dEnd = zone_p + 4;
    else dEnd = zone_p - 4;
    calc_relative_xy(dEnd);
    LA (move_lx,move_ly);
    wait(220);
    if(right_on) dEnd = zone_p + 4;
    else dEnd = zone_p - 4;
    calc_relative_xy(dEnd);
    LA (move_lx,move_ly);
    wait(40);
    if(right_on) dEnd = zone_p + 1;
    else dEnd = zone_p - 1;
    calc_relative_xy(dEnd);
    LA (move_lx,move_ly);
    wait(600);
    LS_BlockOutput = FALSE;
    Get_LS_Output  = TRUE;
}
                         
combo HEEL_to_BALL_ROLL_cmb { 
	  LS_BlockOutput = TRUE;
    set_val(PlayerRun,100);
    RA_UP();  
    LA(0,0);// up     
    wait(w_rstick);
    set_val(PlayerRun,100);
    RA_ZERO ();    // ZERO 
    LA(0,0);
    wait(w_rstick); 
    set_val(PlayerRun,100);
    LA(0,0);
    RA_DOWN ();    // down 
    wait(w_rstick);
    if(right_on) dEnd = zone_p + 1;
    else dEnd = zone_p - 1;
    calc_relative_xy(dEnd);
    LA (move_lx,move_ly);
    wait(200);
    LS_BlockOutput = FALSE;
    Get_LS_Output = TRUE;
} 
combo STUTTER_FEINT_cmb {
	set_val(PaceCtrol,100);// hold L2
	RA_L_R();       // lef/right                    
	wait(w_rstick);
	right_on = !right_on;
	set_val(PaceCtrol,100);// hold L2
	RA_L_R();       // lef/right                    
	wait(w_rstick);
    Get_LS_Output = TRUE;
}
combo JOG_OPENUP_FAKE_SHOT_cmb {
	set_val(PlayerRun,100);
	set_val(CrossBtn,100);  
	wait(40); 
	set_val(PlayerRun,100);
	set_val(CrossBtn,100);  
	set_val(PassBtn,100); 
	wait(60);
	set_val(PlayerRun,100);
	set_val(CrossBtn,0);  
	set_val(PassBtn,100);
	LA_L_R();
	wait(60);
	set_val(PlayerRun,100); 
	LA_L_R();
	wait(300);
    Get_LS_Output = TRUE;
}        
combo STOP_PLAYER_cmb {
  zone_saver(); 
  wait(20);
  wait(100);
  set_val(SprintBtn,100);
  wait(40);
  wait(160);
    Get_LS_Output = TRUE;
}

function zone_saver() {
dEnd = zone_p
calc_relative_xy(dEnd);
LX = move_lx;
LY = move_ly;
}

combo JUGGLING_cmb{
set_val(PaceCtrol,100);
set_val(FinesseShot,100);
wait(100);
set_val(PaceCtrol,100);
wait(100);
    Get_LS_Output = TRUE;
}
int LS_BlockOutput;
///////////////////////////////////////////////////
// ZONE FUNCTION
const int ZONE_P [][] = {
//  X,  Y   
{   0,-100 },//0 UP
{ 100,-100 },//1 Up-Right
{ 100,   0 },//2 Right
{ 100, 100 },//3 Down right
{   0, 100 },//4 Down
{-100, 100 },//5 Down Left
{-100,   0 },//6 Left
{-100,-100 } //7 Left Up 
}

int move_lx, move_ly, zone_p;

function calc_zone(){
    if(get_ival(PS4_LX) >= 35) move_lx = 100;
    else if(get_ival(PS4_LX) <= -35) move_lx = -100;
    else move_lx = 0;
    if(get_ival(PS4_LY) >= 35) move_ly = 100;
    else if(get_ival( PS4_LY) <= -35) move_ly = -100;
    else move_ly = 0;
    
    if(move_lx != 0 || move_ly != 0) {
        zone_p = 0; while(zone_p < 8) {
            if(ZONE_P[zone_p][0] == move_lx && ZONE_P[zone_p][1] == move_ly) {
                break;
            } zone_p += 1;
        }
    }    
}
function calc_relative_xy(d) {
    if(d < 0 ) d = 8 - abs(d);
    else if(d >= 8) d = d - 8;
    move_lx = ZONE_P [d][0];// X
    move_ly = ZONE_P [d][1];// Y
}
//--------------------------------------------------------------
//      Analog Functions                                        
//--------------------------------------------------------------
int LS_Sens_Corect;  
function RA (xx,yy){ 
	set_val(SKILL_STICK_X,xx);
	set_val(SKILL_STICK_Y,yy);
}                  
function LA (x,y){ 
	set_val(MOVE_X,x);
	set_val(MOVE_Y,y);
}                  
function LA_L_R() {          
	if(right_on) {// right      
		set_val(MOVE_X,inv(LY));  
		set_val(MOVE_Y,LX);       
	}                           
	else {       //  left       
	    set_val(MOVE_X,LY );    
	    set_val(MOVE_Y,inv(LX)); 
    }                         
}                              
function RA_L_R() {             
	if(right_on) {// right          
		set_val(SKILL_STICK_X,inv(LY));
		set_val(SKILL_STICK_Y,LX);      
	}                                  
	else {       //  left               
	    set_val(SKILL_STICK_X,LY );     
	    set_val(SKILL_STICK_Y,inv(LX)); 
    }                                
}                                    
function RA_OPP() {                  
	if(!right_on) {// right             
		set_val(SKILL_STICK_X,inv(LY));   
		set_val(SKILL_STICK_Y,LX);        
	}                                   
	else {       //  left               
	    set_val(SKILL_STICK_X,LY );     
	    set_val(SKILL_STICK_Y,inv(LX)); 
    }                                
}                                    
function RA_UP () {                  
	set_val(SKILL_STICK_X,LX );        
	set_val(SKILL_STICK_Y,LY );        
}                                   
function RA_DOWN () {               
	set_val(SKILL_STICK_X,inv(LX) );   
	set_val(SKILL_STICK_Y,inv(LY) );   
}                                  
function RA_ZERO () {             
	set_val(SKILL_STICK_X,0 );      
	set_val(SKILL_STICK_Y,0 );     
}                             

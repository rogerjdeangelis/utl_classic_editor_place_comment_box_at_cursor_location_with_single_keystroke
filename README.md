# utl_place_comment_box_at_cursor_location_with_single_keystroke
Place comment box at cursor location with single keystroke.  Keywords: sas sql join merge big data analytics macros oracle teradata mysql sas communities stackoverflow statistics artificial inteligence AI Python R Java Javascript WPS Matlab SPSS Scala Perl C C# Excel MS Access JSON graphics maps NLP natural language processing machine learning igraph DOSUBL DOW loop stackoverflow SAS community.


    Place comment box at cursor location with single keystroke classic editor

    Best in c;lassic editor, requires prefix area and function keys?

    see github
    https://tinyurl.com/y7w29dh3
    https://github.com/rogerjdeangelis/utl_place_comment_box_at_cursor_location_with_single_keystroke

    Inspired by
    SAS tipster
    https://communities.sas.com/t5/user/viewprofilepage/user-id/192946

    see
    https://tinyurl.com/y9meglyw
    https://communities.sas.com/t5/SAS-Tips-from-the-Community/SAS-Tip-Use-SAS-DM-Commands-to-Save-and-then-Clear-Your-SAS-Log/m-p/47601


    INPUT
    =====

      "d:/txt/box.txt"; (Note /* */ prevents SAS triggers)

    /***************************************************\;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    \****************************************************/



    PROCESS
    =======

      Put this on a fnction key

      cntl I   :a; inc  "d:\txt\box.txt

      Place cursor and then hold cntl down and hit I

      Could put on F1-F12 but I need those for more frequent functions


    OUTPUT
    ======

    Cursor at col 1 line 3

    Command ===>

    00001
    00002
    00003 /***************************************************\;
    00004 *                                                   *;
    00005 *                                                   *;
    00006 *                                                   *;
    00007 *                                                   *;
    00008 *                                                   *;
    00009 *                                                   *;
    00010 *                                                   *;
    00011 *                                                   *;
    00012 *                                                   *;
    00013 \****************************************************/
    00014
    00015
    00015
    00015

    *                _               _       _
     _ __ ___   __ _| | _____     __| | __ _| |_ __ _
    | '_ ` _ \ / _` | |/ / _ \   / _` |/ _` | __/ _` |
    | | | | | | (_| |   <  __/  | (_| | (_| | || (_| |
    |_| |_| |_|\__,_|_|\_\___|   \__,_|\__,_|\__\__,_|

    ;

    data _null_;
     file "d:/txt/box.txt";
     input;
     put _infile_;
     putlog _infile_;
    cards4;
    /***************************************************\;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    *                                                   *;
    \****************************************************/
    ;;;;
    run;quit;

    *          _       _   _
     ___  ___ | |_   _| |_(_) ___  _ __
    / __|/ _ \| | | | | __| |/ _ \| '_ \
    \__ \ (_) | | |_| | |_| | (_) | | | |
    |___/\___/|_|\__,_|\__|_|\___/|_| |_|

    ;
    see process


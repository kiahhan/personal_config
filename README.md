personal_config
===============

Put my personal configuration into this repository


###How do I upgrade oh my zsh, when I got Xcode/iOS license requires admin privileges issue.

    Kiah@MacBook-Pro ~/.oh-my-zsh$ upgrade_oh_my_zsh                   127 ↵
    Upgrading Oh My Zsh


    Agreeing to the Xcode/iOS license requires admin privileges, please re-run as root via sudo.


    There was an error updating. Try again later?
    Kiah@MacBook-Pro ~/.oh-my-zsh$ sudo upgrade_oh_my_zsh

    WARNING: Improper use of the sudo command could lead to data loss
    or the deletion of important system files. Please double-check your
    typing when using sudo. Type "man sudo" for more information.

    To proceed, enter your password, or type Ctrl-C to abort.

    Password:
    sudo: upgrade_oh_my_zsh: command not found


**What do I have to do?**

    Kiah@MacBook-Pro ~/.oh-my-zsh$ sudo xcodebuild -license
    
    You have not agreed to the Xcode license agreements. You must agree to both license agreements below in order to use Xcode.

    Hit the Enter key to view the license agreements at '/Applications/Xcode.app/Contents/Resources/English.lproj/License.rtf'

    IMPORTANT: BY USING THIS SOFTWARE, YOU ARE AGREEING TO BE BOUND BY THE FOLLOWING APPLE TERMS:

    A. MAC SDK AND XCODE AGREEMENT
    B. iOS SDK AGREEMENT

    APPLE INC.
    MAC SDK AND XCODE AGREEMENT

    PLEASE READ THIS MAC SDK AND XCODE AGREEMENT ("LICENSE") CAREFULLY BEFORE USING THE DEVELOPER SOFTWARE (DEFINED BELOW). BY USING THE DEVELOPER SOFTWARE, YOU ARE AGREEING TO BE BOUND BY THE TERMS OF THIS LICENSE.  IF YOU ARE ACCESSING THE DEVELOPER SOFTWARE ELECTRONICALLY, SIGNIFY YOUR AGREEMENT TO BE BOUND BY THE TERMS OF THIS LICENSE BY CLICKING THE "AGREE " BUTTON.  IF YOU DO NOT AGREE TO THE TERMS OF THIS LICENSE, DO NOT USE THE DEVELOPER SOFTWARE AND CLICK “DISAGREE”.

    IMPORTANT NOTE: To the extent that this software may be used to reproduce materials, it is licensed to you only for reproduction of non-copyrighted materials, materials in which you own the copyright, or materials you are authorized or legally permitted to reproduce. If you are uncertain about your right to copy any material, you should contact your legal advisor.

    1. General.
    A. The Apple software, tools, utilities, sample or example code, documentation,


    By typing 'agree' you are agreeing to the terms of the software license agreements. Type 'print' to print them or anything else to cancel, [agree, print, cancel] agree

    You can view the license agreements in Xcode's About Box, or at /Applications/Xcode.app/Contents/Resources/English.lproj/License.rtf

		Kiah@Feis-MacBook-Pro ~/.oh-my-zsh$ upgrade_oh_my_zsh                   master
		Upgrading Oh My Zsh
		From https://github.com/kiahhan/oh-my-zsh
		 * branch            master     -> FETCH_HEAD
		Current branch master is up to date.
		         __                                     __
		  ____  / /_     ____ ___  __  __   ____  _____/ /_
		 / __ \/ __ \   / __ `__ \/ / / /  /_  / / ___/ __ \
		/ /_/ / / / /  / / / / / / /_/ /    / /_(__  ) / / /
		\____/_/ /_/  /_/ /_/ /_/\__, /    /___/____/_/ /_/
		                        /____/
		Hooray! Oh My Zsh has been updated and/or is at the current version.
		To keep up on the latest, be sure to follow Oh My Zsh on twitter: http://twitter.com/ohmyzsh
		Kiah@MacBook-Pro ~/.oh-my-zsh$                                                                                           master
		Kiah@MacBook-Pro ~/.oh-my-zsh$                                                           1 ↵ master


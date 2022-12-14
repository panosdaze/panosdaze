from os import system
from colorama import Fore
import os
import webbrowser
from webbrowser import open_new
import time
import pyautogui
import colorama 
from pyautogui import *
from colorama import *
from os import *
from time import sleep
colorama.init(autoreset=True)
class PS_Gui:
    os.system('cls')
    loading_msg = f'{Fore.LIGHTCYAN_EX}Loading...'
    os.system('cls')
    print(loading_msg)
    time.sleep(1)
    os.system('cls')
    initialising_msg = f'{Fore.LIGHTCYAN_EX}Intialising...'
    print(initialising_msg)
    time.sleep(1)
    os.system('cls')
    def welcome_messages():
        print(f'{Fore.LIGHTGREEN_EX}╔════╦        ')
        print(f'{Fore.LIGHTGREEN_EX}║║══║║  ║════║')
        print(f'{Fore.LIGHTGREEN_EX}║║══║║  ║    ║')
        print(f'{Fore.LIGHTGREEN_EX}║═╦══║  ║ ╚══╣')
        print(f'{Fore.LIGHTGREEN_EX}║ ║     ╠══╗ ║')
        print(f'{Fore.LIGHTGREEN_EX}║ ║     ║    ║')
        print(f'{Fore.LIGHTGREEN_EX}║ ║     ║════║')
        welcome_msg_1 = f'{Fore.LIGHTGREEN_EX}Welcome to {Fore.LIGHTRED_EX}PS ONLINE GUI'
        print(welcome_msg_1)
    welcome_messages()
    def user_path_choose():
        user_path_choose_1 = f'{Fore.LIGHTRED_EX}Enter {Fore.LIGHTGREEN_EX}1 {Fore.LIGHTRED_EX}to use the webbsite GUI {Fore.LIGHTGREEN_EX}(Includes Online Usefull Websites):'
        user_path_choose_2 = f'{Fore.LIGHTRED_EX}Enter {Fore.LIGHTGREEN_EX}2 {Fore.LIGHTRED_EX}to use the game GUI {Fore.LIGHTGREEN_EX}(Includes Famus And Funny Games To Play):'
        print(user_path_choose_1)
        print(user_path_choose_2)  
    user_path_choose()
    while True:
        user_option = input("Enter 1 or 2: ")
        print(f'{Fore.LIGHTRED_EX}Error! {Fore.LIGHTGREEN_EX}Please Enter 1 Or 2')
        if user_option == "1":
            break
        if user_option == "2":
            break
    if user_option == "1":
        os.system('cls')
        print(loading_msg)
        time.sleep(1)
        os.system('cls')
        print(f'{Fore.LIGHTGREEN_EX}Webbrowser GUI')
        print(f'{Fore.LIGHTGREEN_EX}1 {Fore.LIGHTRED_EX}Google')
        print(f'{Fore.LIGHTGREEN_EX}2 {Fore.LIGHTRED_EX}Youtube')
        print(f'{Fore.LIGHTGREEN_EX}3 {Fore.LIGHTRED_EX}Facebook')
        print(f'{Fore.LIGHTGREEN_EX}4 {Fore.LIGHTRED_EX}Twitter')
        print(f'{Fore.LIGHTGREEN_EX}5 {Fore.LIGHTRED_EX}Wikipedia')
        print(f'{Fore.LIGHTGREEN_EX}6 {Fore.LIGHTRED_EX}Instagram')
        print(f'{Fore.LIGHTGREEN_EX}7 {Fore.LIGHTRED_EX}Baidu')
        print(f'{Fore.LIGHTGREEN_EX}8 {Fore.LIGHTRED_EX}Yahoo')
        print(f'{Fore.LIGHTGREEN_EX}9 {Fore.LIGHTRED_EX}Whatsapp')
        print(f'{Fore.LIGHTGREEN_EX}10 {Fore.LIGHTRED_EX}Viber')
        while True:
            starting_browser_msg = f'{Fore.LIGHTCYAN_EX}Starting Browser...'
            browser_succesfully_started = f'{Fore.LIGHTGREEN_EX}Browser Succesfully Started!'
            user_websites_choice = input("Enter your choice: ")
            print(f'{Fore.LIGHTRED_EX}Error! {Fore.LIGHTGREEN_EX}Please Enter a Number Between 1-10')
            if user_websites_choice == "1":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "2":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "3":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "4":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "5":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "6":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "7":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "8":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "9":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
            if user_websites_choice == "10":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(2)
                print(browser_succesfully_started)
                break
        if user_websites_choice == '1':
            webbrowser.open_new('www.google.com')
        if user_websites_choice == '2':
            webbrowser.open_new('www.youtube.com')
        if user_websites_choice == '3':
            webbrowser.open_new('www.Facebook.com')
        if user_websites_choice == '4':
            webbrowser.open_new('www.Twitter.com')
        if user_websites_choice == '5':
            webbrowser.open_new('www.Wikipedia.org')
        if user_websites_choice == '6':
            webbrowser.open_new('www.Instagram.com')
        if user_websites_choice == '7':
            webbrowser.open_new('www.Baidu.com')
        if user_websites_choice == '8':
            webbrowser.open_new('www.Yahoo.com')
        if user_websites_choice == '9':
            webbrowser.open_new('www.Whatsapp.com')
        if user_websites_choice == '10':
            webbrowser.open_new('www.Viber.com')
    if user_option == '2':
        os.system('cls')
        print(loading_msg)
        time.sleep(1)
        os.system('cls')
        print(f'{Fore.LIGHTGREEN_EX}Game GUI')
        print(f'{Fore.LIGHTGREEN_EX}1 {Fore.LIGHTRED_EX}PUBG')
        print(f'{Fore.LIGHTGREEN_EX}2 {Fore.LIGHTRED_EX}Minecraft')
        print(f'{Fore.LIGHTGREEN_EX}3 {Fore.LIGHTRED_EX}Apex Legends')
        print(f'{Fore.LIGHTGREEN_EX}4 {Fore.LIGHTRED_EX}Fortnite')
        print(f'{Fore.LIGHTGREEN_EX}5 {Fore.LIGHTRED_EX}Counter Strike')
        print(f'{Fore.LIGHTGREEN_EX}6 {Fore.LIGHTRED_EX}HearthStone')
        print(f'{Fore.LIGHTGREEN_EX}7 {Fore.LIGHTRED_EX}League Of Legends')
        print(f'{Fore.LIGHTGREEN_EX}8 {Fore.LIGHTRED_EX}Call Of Duty')
        print(f'{Fore.LIGHTGREEN_EX}9 {Fore.LIGHTRED_EX}Among us')
        print(f'{Fore.LIGHTGREEN_EX}10 {Fore.LIGHTRED_EX}Krunker')
        while True:
            starting_browser_msg = f'{Fore.LIGHTCYAN_EX}Starting Browser...'
            browser_succesfully_started = f'{Fore.LIGHTGREEN_EX}Browser Succesfully Started!'
            user_game_choice = input("Enter your choice: ")
            print(f'{Fore.LIGHTRED_EX}Error! {Fore.LIGHTGREEN_EX}Please Enter a Number Between 1-10')
            if user_game_choice == "1":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "2":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "3":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "4":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "5":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "6":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "7":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "8":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "9":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
            if user_game_choice == "10":
                os.system('cls')
                print(starting_browser_msg)
                time.sleep(1)
                print(browser_succesfully_started)
                break
        if user_game_choice == '1':
            webbrowser.open_new('https://na.battlegrounds.pubg.com/')
        if user_game_choice == '2':
            webbrowser.open_new('https://www.minecraft.net/en-us')
        if user_game_choice == '3':
            webbrowser.open_new('https://www.ea.com/games/apex-legends')
        if user_game_choice == '4':
            webbrowser.open_new('https://www.epicgames.com/fortnite/en-US/home')
        if user_game_choice == '5':
            webbrowser.open_new('https://blog.counter-strike.net/')
        if user_game_choice == '6':
            webbrowser.open_new('https://hearthstone.blizzard.com/en-us')
        if user_game_choice == '7':
            webbrowser.open_new('https://www.leagueoflegends.com/el-gr/')
        if user_game_choice == '8':
            webbrowser.open_new('https://www.callofduty.com/')
        if user_game_choice == '9':
            webbrowser.open_new('https://store.steampowered.com/app/945360/Among_Us/')
        if user_game_choice == '10':
            webbrowser.open_new('https://www.krunker.io')

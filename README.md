
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

## Följande grundsyn gäller dugga-svar:
Det som har gjorts är att namnet på appen har ändrats till JesperApp, internet acces har lagts till i android manifest, ett WebView element har skapats i activity_main, Webview fick ett ID tilldelat till sig, en private member "mywebview" lades till samt att en kopia av denna lades till i "oncreate" sedan lokaliserades detta element via "findveiwbyid"
En ny webbview klient skapades som fästes via webbview, efter detta så aktiverades javascripts-utförande, efter detta skapades en mapp i "app" där en html fil lades till samt en img directory, när detta var klart så lades en external webpage in som var "his.se" samt en internal webpage "file:android_asset/about.html", det sista som gjordes var att göra så att valen för internal samt external webpage fungerade via dropdown menyn.
- Ett kortfattat svar är att föredra. Svar som är längre än en sida text (skärmdumpar och programkod exkluderat) är onödigt långt.
- Svaret skall ha minst en snutt programkod.
- Svaret skall inkludera en kort övergripande förklarande text som redogör för vad respektive snutt programkod gör eller som svarar på annan teorifråga.
- Svaret skall ha minst en skärmdump. Skärmdumpar skall illustrera exekvering av relevant programkod. Eventuell text i skärmdumpar måste vara läsbar.
- I de fall detta efterfrågas, dela upp delar av ditt svar i för- och nackdelar. Dina för- respektive nackdelar skall vara i form av punktlistor med kortare stycken (3-4 meningar).

Programkod ska se ut som exemplet nedan. Koden måste vara korrekt indenterad då den blir lättare att läsa vilket gör det lättare att hitta syntaktiska fel.

```
<uses-permission android:name="android.permission.INTERNET" />

    private WebView myWebView;
    
     public void showExternalWebPage(){
        myWebView.loadUrl("https://www.his.se/");
        
         public void showInternalWebPage(){
        myWebView.loadUrl("file:///android_asset/about.html");


protected void onCreate(Bundle savedInstanceState) {
        setContentView(R.layout.activity_main);
        Toolbar toolbar = findViewById(R.id.toolbar);
        setSupportActionBar(toolbar);
        myWebView = findViewById(R.id.my_WebView);
        myWebView.setWebViewClient(new WebViewClient()); // Do not open in Chrome
        WebSettings webSettings = myWebView.getSettings();
        webSettings.setJavaScriptEnabled(true);
        myWebView.loadUrl("file:///android_asset/about.html");
        super.onCreate(savedInstanceState);
        
        showExternalWebPage();
        
        showInternalWebPage();
            

```

Bilder läggs i samma mapp som markdown-filen.

![](internal%20img.png)
![](external%20img.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.

# Accordion

{% hint style="info" %}
Accordion with image on the right
{% endhint %}

![](../.gitbook/assets/accordion-iright-2x.png)

```markup
<div class="container">
  <div class="row">
    <div class="col-lg-6 col-md-12">
      <div class="accordion" id="accordionExample">
        <div class="card">
          <div class="card-header" id="headingOne">
            <h2 class="mb-0">
              <button
                class="btn btn-link btn-block text-left"
                type="button"
                data-toggle="collapse"
                data-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                Testmanagement
              </button>
            </h2>
          </div>
  
          <div
            id="collapseOne"
            class="collapse show"
            aria-labelledby="headingOne"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Effektives Testmanagement ist das Rückgrat eines jeden
              durchgängigen Softwareentwicklungsprozesses. Dabei gilt es,
              bewährte Testprozesse und Tools smart miteinander zu
              kombinieren und perfekt aufeinander abzustimmen.
              Testmanagement umfasst jedoch noch weit mehr. So gilt es, die
              notwendigen Tests effektiv zu planen, zu überwachen,
              auszuwerten und für eine durchgehende Kommunikation zu sorgen.
              Dieses Vorgehen stellt sicher, dass die Software pünktlich und
              in perfekter Qualität geliefert wird. Smartes Testmanagement
              schafft jedoch auch Zeit, sodass auch ungeplante
              Änderungswünsche und Features den Release-Termin nicht
              gefährden. Wir bieten Ihnen nicht nur Unternehmensberatung,
              sondern auch kompetentes Testmanagement mit klassischen und
              agilen Methoden, sodass Ihre Digitalisierungs- und
              Transformationsprojekte auch den höchsten Qualitätsansprüchen
              gerecht werden.
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingTwo">
            <h2 class="mb-0">
              <button
                class="btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                Testautomatisierung
              </button>
            </h2>
          </div>
          <div
            id="collapseTwo"
            class="collapse"
            aria-labelledby="headingTwo"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Testautomatisierung spart nicht nur Zeit, sondern sorgt auch
              dafür, dass Ihre Software immer in bester Qualität
              ausgeliefert wird. Ganz gleich ob SAP-Testautomation,
              E2E-Automation oder die Automatisierung Ihrer
              Regressionstests, unsere erfahrenen Softwaretester in Hamburg
              stehen Ihnen bei allen Themen mit Rat und Tat zur Seite. Wir
              zeigen Ihnen, wie Sie Ihre vorhandenen Softwaretests
              nachhaltig automatisieren können, welche Tools sich wirklich
              lohnen und wir übernehmen auf Wunsch auch die
              Testautomatisierung aller Komponenten und Module.
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingThree">
            <h2 class="mb-0">
              <button
                class="btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                ISTQB Schulungen
              </button>
            </h2>
          </div>
          <div
            id="collapseThree"
            class="collapse"
            aria-labelledby="headingThree"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Wir bieten Ihnen professionelles ISTQB Training mit
              unterschiedlichen Schwerpunkten. All unsere Seminare werden
              von erfahrenen Trainern mit viel praktischer Berufserfahrung
              geleitet, sodass Ihre Mitarbeiter nicht nur von fundierten
              theoretischen Inhalten, sondern auch von Best Practices
              profitieren. Unser Portfolio umfasst sowohl Einstiegskurse als
              auch ISTQB Schulungen für erfahrene Mitarbeiter, die ein
              Advanced Level anstreben.
            </div>
          </div>
        </div>
      </div>
    </div>
  
    <div class="col-lg-6 col-md-12 imgright">
      <img
        src="/src/images/testa.jpg"
        alt="Testautomatisierung"
        class="img-fluid"
      />
    </div>
  </div>
</div>
```

{% hint style="info" %}
Accordion with image on the left
{% endhint %}

![](../.gitbook/assets/accordion-ileft-2x.png)

```markup
<div class="container">
  <div class="row">
    <div class="col-lg-6 col-md-12 imgright">
      <img
        src="/src/images/devops.jpg"
        alt="Testautomatisierung"
        class="img-fluid"
      />
    </div>
    <div class="col-lg-6 col-md-12">
      <div class="accordion" id="accordionExample">
        <div class="card">
          <div class="card-header" id="headingOne">
            <h2 class="mb-0">
              <button
                class="btn btn-link btn-block text-left"
                type="button"
                data-toggle="collapse"
                data-target="#Individualentwicklung"
                aria-expanded="true"
                aria-controls="Individualentwicklung"
              >
                Individualentwicklung
              </button>
            </h2>
          </div>

          <div
            id="Individualentwicklung"
            class="collapse show"
            aria-labelledby="headingOne"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Unternehmen sind einzigartig, wodurch nicht jede
              Standardsoftware zu jedem Unternehmen passt. Wir bieten Ihnen
              daher Individualentwicklung, die speziell auf Ihr Unternehmen
              und Ihre Prozesse angepasst ist und die Sie bei Ihren
              täglichen Aufgaben unterstützt und nicht behindert. Ganz
              gleich, ob Java-Entwicklung, Microservices,
              Frontend-Entwicklung oder Backend-Entwicklung, mit einer
              Lösung aus unserem Haus profitieren Sie immer von perfektem
              Service und erstklassiger Software, die den höchsten
              Ansprüchen gerecht wird.
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingTwo">
            <h2 class="mb-0">
              <button
                class="btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#DevOps"
                aria-expanded="false"
                aria-controls="DevOps"
              >
                DevOps
              </button>
            </h2>
          </div>
          <div
            id="DevOps"
            class="collapse"
            aria-labelledby="headingTwo"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Die digitale Transformation führt dazu, dass wir überall auf
              Software treffen. So macht der digitale Wandel auch vor
              Banken, Versicherungen, der Industrie und dem Handel nicht
              Halt. Damit die komplexen Systeme reibungslos funktionieren
              und dauerhaft verfügbar sind, bedarf es einer neuen
              Herangehensweise. Wir zeigen Ihnen, wie Sie mit der Hilfe von
              smarten Prozessen und modernen Tools eine Kultur verwirklichen
              können, in der Menschen gemeinsam, über Abteilungsgrenzen
              hinweg, an und mit der Software arbeiten, diese
              weiterentwickeln und konstant verbessern.
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingThree">
            <h2 class="mb-0">
              <button
                class="btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#Web-Entwicklung"
                aria-expanded="false"
                aria-controls="Web-Entwicklung"
              >
                Web-Entwicklung
              </button>
            </h2>
          </div>
          <div
            id="Web-Entwicklung"
            class="collapse"
            aria-labelledby="headingThree"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Der eigene digitale Webauftritt ist die Visitenkarte eines
              jeden Unternehmens. Damit auch Ihr Webauftritt bei Ihren
              Besuchern einen bleibenden und vor allem positiven Eindruck
              hinterlässt, kümmern sich unsere erfahrenen Web-Entwickler um
              den professionellen Webauftritt Ihres Unternehmens. Angefangen
              bei der Konzeption und dem Design, über die Realisierung bis
              hin zur Wartung übernehmen wir für Sie sämtliche Aufgaben,
              sodass Ihre Webpräsenz Ihre Kunden nicht nur überzeugt,
              sondern auch begeistert.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```


```mermaid
gantt
    title @MarigonaRamadaniHoti's To-Do Zeitstrahl
    dateFormat  YYYY-MM-DD

    section Planung 📝
    Konzeptphase         :done,    p1, 2025-03-01, 2025-03-10
    Anforderungsanalyse  :active,  p2, 2025-03-11, 2025-03-20

    section Entwicklung 💻
    Backend-Architektur  :        dev1, 2025-03-21, 2025-04-05
    Frontend-Design      :        dev2, 2025-04-06, 2025-04-20
    API-Integration      :after dev1, 2025-04-21, 2025-05-01

    section Test & Optimierung 🔍
    Testphase Backend    :after dev1, test1, 2025-05-02, 2025-05-07
    Testphase Frontend   :after dev2, test2, 2025-05-08, 2025-05-14
    Bugfixing            :after test1, test2, fix1, 2025-05-15, 2025-05-20

    section Deployment 🚀
    Finaler Review       :after fix1, dep1, 2025-05-21, 2025-05-25
    Veröffentlichung     :after dep1, dep2, 2025-05-26, 2025-05-30

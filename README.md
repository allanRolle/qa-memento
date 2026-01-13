# Memento

Questions et réponses pour entretien

<!-- <details>
    <summary>Hello</summary>
    <p>World !</p>
</details> -->
<!-- <ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul> -->

## Soft skills

<details>
    <summary>Quelles sont les qualités d'un bon testeur ?</summary>
    <p>Devenir un bon testeur logiciel repose sur une combinaison de rigueur, curiosité technique et excellentes compétences en communication. Le rôle va bien au-delà de l’exécution de tests : il s’agit d’être un garant de la qualité en détectant les anomalies, en comprenant les attentes utilisateurs et en collaborant étroitement avec les développeurs. Une bonne formation, une veille technologique constante et l’acquisition de certifications reconnues comme l’ISTQB sont des leviers clés pour exceller dans ce métier en pleine expansion.</p>
</details>

<details>
    <summary>Conseils et astuces pour devenir un bon testeur</summary>
    <ul>
        <li>Comprendre le cycle de développement logiciel : Apprenez les différentes phases (conception, développement, test, déploiement) et le rôle du testeur à chaque étape.</li>
        <li>Acquérir les bases techniques : Formez-vous aux langages de programmation, aux bases de données, aux réseaux et aux protocoles web pour mieux comprendre les applications testées.</li>
        <li>Maîtriser les types de tests : Apprenez à réaliser des tests fonctionnels, non fonctionnels (performance, sécurité), manuels et automatisés.</li>
        <li>Développer des cas de test solides : Apprenez à analyser les spécifications, à concevoir des scénarios de test exhaustifs et à couvrir les cas d’utilisation réels et limites.</li>
        <li>Utiliser les outils de test : Pratiquez avec des outils comme Jira pour le suivi de bugs, Selenium pour l’automatisation, et TestRail pour la gestion des tests.</li>
        <li>Documenter et communiquer efficacement : Rédigez des rapports de test clairs, précis et complets, et soyez capable d’expliquer les bugs aux développeurs de manière constructive.</li>
        <li>Adopter une attitude proactive : Soyez créatif dans la recherche de bugs, sortez des sentiers battus, et proposez des améliorations de processus.</li>
        <li>Travailler en équipe : Collaborez activement avec les développeurs, chefs de projet et autres parties prenantes dans un esprit agile.</li>
        <li>Se certifier : Préparez la certification ISTQB pour valider vos compétences et renforcer votre crédibilité professionnelle.</li>
        <li>Apprendre en continu : Restez à jour avec les nouvelles technologies, frameworks et bonnes pratiques via des blogs, webinaires et communautés de testeurs.</li>
    </ul>
</details>

## Général

<details>
    <summary>Astuce pour rédiger un plan de test</summary>
    <ul>
        <li>Quoi ?</li>
        <li>Comment ?</li>
        <li>Quand ?</li>
        <li>Qui ?</li>
    </ul>
</details>

<details>
    <summary>Astuce pour rédiger un cas de test</summary>
    <ul>
        <li>Étapes détaillés</li>
        <li>Données</li>
        <li>Résultat attendus</li>
    </ul>
</details>

<details>
    <summary>Quelles sont les raisons d'adopter des techniques de test basées sur l'expérience ?</summary>
    <ul>
        <li>L’exploitation des connaissances et de l’intuition des testeurs expérimentés, notamment sur les points faibles historiques du système.</li>
        <li>La détection de défauts dans les zones à haut risque ou mal couvertes par d’autres techniques.</li>
        <li>La rapidité d’exécution, car ces techniques ne nécessitent pas de préparation formelle comme l’écriture de cas de test détaillés.</li>
        <li>L’adaptabilité à des situations où les spécifications sont incomplètes ou absentes.</li>
        <li>Le complément idéal aux techniques systématiques (boîte noire ou boîte blanche), en apportant une couverture supplémentaire basée sur le savoir-faire pratique.</li>
    </ul>
</details>
<details>
    <summary>Qu'est-ce qu'un cachier de charges ? Un document de spécifications ? Quelle est la différence entre les deux ?</summary>
    <p>Un cahier des charges est effectivement un document de spécifications. C'est un document contractuel qui définit de manière précise et détaillée les besoins, les exigences et les contraintes d'un projet. Il contient généralement :</p>
    <ul>
        <li>L'objectif du projet et le contexte</li>
        <li>Les spécifications fonctionnelles (ce que doit faire le produit/service)</li>
        <li>Les spécifications techniques (comment cela doit être réalisé)</li>
        <li>Les contraintes (budget, délais, normes à respecter)</li>
        <li>Les critères de qualité et de validation</li>
        <li>Les livrables attendus</li>
        <li>Le cahier des charges sert de référence commune entre le client (qui exprime ses besoins) et le prestataire ou l'équipe projet (qui réalise). Il peut être :
            <ul>
                <li><strong>Fonctionnel:</strong> axé sur les besoins et résultats attendus (le "quoi")</li>
                <li><strong>Technique:</strong> détaillant les solutions et moyens à mettre en œuvre (le "comment")</li>
            </ul>
        </li>
    </ul>
    <p>C'est un outil essentiel en gestion de projet, que ce soit pour du développement logiciel, de la construction, du design, ou tout autre domaine professionnel. La différence est que le cahier de charges n'est pas modifiable, au contraire des spécifications. Le cachier des charges est le cadre global. Les spécifications fonctionnelles décrivent quoi faire, tandis que les spécifications techniques décrivent comment faire.</p>
</details>

<details>
    <summary>Quelle est la différence entre un bug majeur et un bug mineur ?</summary>
    <p>bug majeur => bug qui touche une fonctionnalité majeure (ex: application plante au démarrage)</p>
    <p>bug mineur => bug qui touche une fonctionnalité mineur (fautes d'orthographe)</p>
</details>

## Automatisation

<details>
    <summary>Quels sont les principaux types de tests automatisés en QA ?</summary>
    <p>L’automatisation ne se limite pas aux tests E2E. Elle intervient à plusieurs niveaux pour sécuriser la qualité logicielle.L’objectif n’est pas d’automatiser tout, mais d’automatiser au bon niveau.</p>
    <ul>
        <li>Tests unitaires : vérifient les fonctions ou méthodes individuellement</li>
        <li>Tests d’intégration : valident les échanges entre composants (API, services, BDD)</li>
        <li>Tests End-to-End (E2E) : reproduisent un parcours utilisateur complet</li>
        <li>Tests de non-régression : garantissent qu’une évolution n’a rien cassé</li>
        <li>Smoke tests : contrôlent rapidement les fonctionnalités essentielles</li>
        <li>Tests UI : vérifient le comportement et l’affichage de l’interface</li>
        <li>Tests API : testent la logique métier sans passer par l’UI</li>
        <li> Tests de performance : mesurent stabilité et temps de réponse</li>
        <li>Tests de sécurité (basique) : détectent certaines vulnérabilités connues</li>
        <li>Automatiser, c’est : gagner du temps, limiter les erreurs humaines et sécuriser les releases via la CI/CD</li>
    </ul>
</details>

<details>
    <summary>Quels types de cas de tests sont favorables à l'automatisation?</summary>
    <ul>
        <li>TNR (tests de non-regression)</li>
        <li>Tests stables</li>
        <li>Tests répétitifs</li>
        <li>Tests d'acceptation (BDD)</li>
        <li>Tests de la même application sur plusieurs environnements (iOS, mobile)</li>
    </ul>
</details>

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

## 🫂Soft skills

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

## 🪲Général

<details>
    <summary>Cycle de vie d'un QA ?</summary>
    <p><img src='img/qa-cycle.jpg'></p>
</details>

<details>
    <summary>Qu'est-ce qu'une solide culture QA ?</summary>
    <div>
        Une solide culture QA (Quality Assurance) est un ensemble de pratiques, valeurs et mentalités qui place la qualité au cœur du processus de développement. Voici ses caractéristiques principales :
    <h2>Principes fondamentaux:</h2>
    <ul>
        <li><strong>Responsabilité partagée</strong>: La qualité n'est pas uniquement la responsabilité de l'équipe QA, mais de tous (développeurs, product managers, designers)</li>
        <li><strong>Prévention plutôt que détection</strong>: Anticiper les problèmes en amont plutôt que de les corriger après coup</li>
        <li><strong>Tests continus </strong>: Intégration des tests à chaque étape du développement (CI/CD)</li>
    </ul>
    <h2>Pratiques clés</h2>
    <ul>
        <li><strong>Automatisation</strong>: Tests unitaires, d'intégration et end-to-end automatisés</li>
        <li><strong>Documentation</strong>: Spécifications claires, critères d'acceptation bien définis</li>
        <li><strong>Feedback rapide</strong>: Boucles de retour courtes pour identifier et corriger rapidement les bugs</li>
        <li><strong>Revues de code</strong>: Validation par les pairs avant intégration</li>
        <li><strong>Tests exploratoires</strong>: Compléter l'automatisation par des tests manuels créatifs</li>
    </ul>
    <h2>Mentalité</h2>
    <ul>    
        <li><strong>Culture du "shift-left" </strong>: Impliquer la QA dès la conception, pas seulement en fin de cycle</li>
        <li><strong>Amélioration continue</strong>: Rétrospectives régulières, analyse des incidents</li>
        <li><strong>Transparence</strong>: Communication ouverte sur les problèmes de qualité</li>
        <li><strong>Empathie utilisateur </strong>: Toujours penser à l'expérience finale</li>
    </ul>
    <p>Une solide culture QA réduit les bugs en production, accélère les livraisons et améliore la satisfaction client.</p>
</details>

<details>
    <summary>Qu'est-ce que le test logiciel ?</summary>
    <p>Le test ogiciel consiste à vérifier que le logiciel répond aux exigences, fonctionne correctement et apporte de la valeur à l'utilisateur tout en détectant les anomalies.</p>
</details>

<details>
    <summary>Quelle est la différence entre bug, défaut et erreur ?</summary>
    <ul>
        <li><strong>Erreur</strong>: faute humaine (développeur, PO, QA)</li>
        <li><strong>Défaut / Bug</strong>: anomalie dans le code</li>
        <li><strong>Défaillance</strong>: comportement incorrect observé à l'exécution</li>
    </ul>
</details>

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
    <summary>Combien de formats pour écrire un cas de test?</summary>
    <ul>
        <li>Format classique (préconditions / actions / résultats attendus)</li>
        <li>Format Gherkin (BDD)</li>
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

<details>
    <summary>Quelle est la différence entre tests fonctionnels / non fonctionnels ?</summary>
    <ul>
        <li><strong>Fonctionnels</strong>: vérifient ce que fait le système par rapport aux exigences</li>
        <li><strong>Non fonctionnels</strong>: performance, sécurité, compatibilité, accessibilité</li>
    </ul>
</details>
 
<details>
    <summary>Qu'est-ce qu'un test de régression ?</summary>
    <p>Un test de régression vérifie que les nouvelles modifications n'ont pas cassé les fonctionnalités existantes.</p>
</details>

<details>
    <summary>KPI QA importants ?</summary>
    <ul>
        <li>Taux de couverture</li>
        <li>Taux de réussite</li>
        <li>Nombre de bugs bloquants</li>
        <li>Temps d'exécution</li>
    </ul>
</details>

<details>
    <summary>Pourquoi toi et pas un autre ?</summary>
    <p>Je combine qualité fonctionnelle, automatisation et vision produit, avec une forte capacité d’adaptation et un esprit d’amélioration continue. Je suis un profil polyvalent, je veux monter en compétences en DevOps et l'IA.</p>
</details>

<details>
    <summary>Qu'est-ce qu'une stratégie de test?</summary>
    <p>Une stratégie de test, ce n’est pas une liste de cas de test. C’est un cadre de décision. Pour être efficace, elle repose sur 5 piliers clés :</p>
    <span>1. Les objectifs</span>
    <p>Pourquoi teste-t-on ? Réduire le risque ? Sécuriser un flux critique ?</p>
    <span>2. Les risques</span>
    <p>On ne teste pas tout. On teste ce qui compte vraiment.</p>
    <span>3. Les niveaux et types de tests</span>
    <p>Un équilibre clair entre unitaires, intégration, E2E, exploratoire, auto</p>
    <span>4. L'organisation et les rôles</span>
    <p>Qui teste quoi, quand, et avec quelle responsabilité ?</p>
    <span>5. Le pilotage par la valeur</span>
    <p>Des indicateurs utiles, pas des vanity metrics.</p>
    <p>Une bonne stratégie de test ne vise pas la couverture maximale, mais la maîtrise du risque.</p>
</details>

## 📈Agile

<details>
    <summary>Quel est le rôle du QA en Agile ?</summary>
    <ul>
        <li>Participer à la rédaction des User Stories</li>
        <li>Définir les critères d'acceptation (complétes, sans ambiguïtés et testables)
        <li>Tester</li>
        <li>Garantir la qualité avant la livraision</li>
    </ul>
</details>

<details>
    <summary>Qu'est-ce que la Definition of Done ?</summary>
    <p>Ensemble de critères garantissant qu'une User Story est terminée, testée et livrable.</p>
</details>

<details>
    <summary>Qu'est-ce qu'une User Story ?</summary>
    <p>Description simple d'un besion utilisateur:</p>
    <p>En tant que... je veux.... afin de...</p>
</details>

<details>
    <summary>Différence entre critère d'acceptation et Definiton of Done ?</summary>
    <div class="ih-TJeJGAB7RWy43i3OeTw==">
<div class="c+qhpcvP6H3VCSU9BgHRlQ=="><table class="zxqV+AyRUca+MLhV37xZ3A=="><thead class="vws+0UuF+kO6CYMvFHvtZQ=="><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><th class="Twce1OmS+ZcG-oo8+adRMg==">Caractéristique</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Critère d'Acceptation</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Définition de "Done" (DoD)</th></tr></thead><tbody class="o4qKFCTY3cX9YjCR2ocmKA=="><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Objectif</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Vérifier si une <em>fonctionnalité spécifique</em> répond aux besoins du client/utilisateur.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Définir les <em>conditions générales</em> pour considérer un élément de travail (fonctionnalité, tâche, sprint) comme terminé.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Portée</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Spécifique à une fonctionnalité ou une user story.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Applicable à l'ensemble du projet ou du sprint.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Qui les définit ?</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Collaboration entre l'équipe de développement, le Product Owner et les utilisateurs/clients.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Définie par l'équipe de développement, souvent en collaboration avec les parties prenantes.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Quand sont-ils utilisés ?</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Pendant la phase de développement et de test d'une fonctionnalité.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Avant le début du sprint ou du projet, et régulièrement révisée.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Nature</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Décrivent le comportement attendu de la fonctionnalité.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Décrivent les standards de qualité, les processus et les livrables requis.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Exemples de critères d'acceptation</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">- L'utilisateur peut se connecter avec un email et un mot de passe.  - Le bouton "Soumettre" est activé après avoir rempli tous les champs obligatoires.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">- Tout le code est revu par un pair. - Tous les tests unitaires passent. - La documentation est à jour. - Le code est intégré à la branche principale.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Format</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Généralement formulés en langage naturel, souvent sous forme de "Given/When/Then".</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Liste de points vérifiables.</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Focus</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère d'Acceptation">Fonctionnalité et expérience utilisateur.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Définition de &quot;Done&quot; (DoD)">Qualité, stabilité et conformité.</td></tr></tbody></table></div>
<p><strong>En résumé :</strong></p>
<ul>
<li>Les <strong>critères d'acceptation</strong> valident <em>si</em> une fonctionnalité fonctionne comme prévu.</li>
<li>La <strong>définition de "Done"</strong> garantit <em>comment</em> le travail est réalisé et livré.</li>
</ul>
<p>Les deux sont essentiels pour le succès d'un projet Agile.</p></div>
</details>

<details>
    <summary>Qu'est-ce qu'un critère d'acceptation ?</summary>
    <p>Condition permettant de dire si une User Story est acceptée ou rejetée.</p>
</details>

<details>
    <summary>Quelle est la différence entre User Story et cas de test ?</summary>
    <ul>
        <li>User Story: besoin métier</li>
        <li>Cas de test: validation technique / fonctionnelle</li>
    </ul>
</details>

<details>
    <summary>Qui est responsable de la qualité en Agile ?</summary>
    <p>La qualité est une responsabilité collective: développeurs, QA, PO et équipe ensemble</p>
</details>

<details>
    <summary>Le QA peut-il refuser une User Story ?</summary>
    <p>Le QA donne un avis qualité, mais la décision finale revient au Product Owner selon la valeur métier.</p>
</details>

<details>
    <summary>Que faire si une User Story est mal définie ?</summary>
    <p>Il faut demander des clarifications, aider à la définition des critères d'acceptation avant le développement.</p>
</details>

<details>
    <summary>Peut-on avoir des bugs en production en Agile ?</summary>
    <p>Oui, c'est possible. L'agilité vise à réduire le risque, pas à l'éliminer totalement. L'important est la réactivité.</p>
</details>

<details>
    <summary>Peut-on modifier une User Story pendant le sprint ?</summary>
    <p>Oui, si l'impact est maîtriser et validé par le PO, tout en respectant l'objectif du sprint.</p>
    <p><strong>Example:</strong></p>
    <p>Je travaille comme QA dans une équipe Scrum.<br/>Sprint de 2 semaines<br/>Produit: application mobile de paiement<br/>Une User Story importante arrive en fin de sprint, mais:</p>
    <ul>
        <li>Les critères d'acceptation sont flous</li>
        <li>Le développeur a terminé tard</li>
        <li>Le PO veut livrer quand même</li>
    </ul>
    <p>Que faire en tant que QA ?</p>
    <p>Je vérifie d'abord les critères d'acceptation. J'identifie les risques. Je communique clairement avec le PO et l'équipe pour décider si la User Story est livrable ou non.</p>
</details>

<details>
    <summary>La User Story n'a pas de critères d'acceptation clairs. Que faire ?</summary>
    <p>Demander une clarification immédiate avec le PO (3 amigos) et proposer des critères d'acceptation basés sur le besoin métier avant d'exécuter les tests.</p>
</details>

<details>
    <summary>Que faire si l'on trouve un bug bloquant en fin de sprint ?</summary>
    <p>Je le déclare immédiatement. J'évalue la sévérité. J'informe le PO et on décide ensemble s'il faut corriger, reporter ou sortir la User Story du sprint.</p>
    <ul>
        <li>Transparence</li>
        <li>Priorisation métier</li>
        <li>Décision collective</li>
    </ul>    
</details>

<details>
    <summary>La User Story est livrée avec un bug. Est-ce un échec du QA ?</summary>
    <p>Non. Le QA a identifié le risque et informé. La qualité est une responsabilité collective, pas individuelle.</p>
</details>

<details>
    <summary>Que dire en rétrospective ?</summary>
    <p>Expliquer ce qui a bien fonctionné, ce qui a posé problème et proposer des actions concrètes pour améliorer la qualité dès le début du sprint</p>
</details>

## 💻Automatisation

<details>
    <summary>Pourquoi automatiser les tests ?</summary>
    <ul>
        <li>Gain de temps</li>
        <li>Réduction des erreurs huamaines</li>
        <li>Exécution répétables</li>
        <li>Meilleure couverture de tests</li>
    </ul>
</details>

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

<details>
    <summary>Qu'est-ce que la méthode BDD ?</summary>
    <p>La méthode BDD (Behavior-Driven Development) est une approche de développement logiciel qui étend le TDD (Test-Driven Development) en se concentrant sur le comportement attendu de l'application plutôt que sur les tests techniques</p>
    <p>Principes clés<p>
    <ul>
        <li><strong>Langage naturel</strong> : Les scénarios sont écrits dans un langage compréhensible par tous (développeurs, testeurs, clients) en utilisant la syntaxe Gherkin :<br/>
        - <strong>Given</strong>: contexte<br/>  
        - <strong>When</strong>: action effectuée<br/>  
        - <strong>Then</strong>: résultat attendu<br/>  
       </li>  
       <li><strong>Collaboration</strong> : Encourage la communication entre les équipes techniques et métier pour définir ensemble les comportements attendus</li>
        <li><strong>Documentation vivante</strong> : Les scénarios BDD servent à la fois de spécifications, de tests automatisés et de documentation</li> 
    </ul>
</details>

<details>
    <summary>Différence entre Selenium / Cypress / Playwright ?</summary>
    <div class="ih-TJeJGAB7RWy43i3OeTw==">
    <div class="c+qhpcvP6H3VCSU9BgHRlQ=="><table class="zxqV+AyRUca+MLhV37xZ3A=="><thead class="vws+0UuF+kO6CYMvFHvtZQ=="><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><th class="Twce1OmS+ZcG-oo8+adRMg==">Critère</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Selenium</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Cypress</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Playwright</th></tr></thead><tbody class="o4qKFCTY3cX9YjCR2ocmKA=="><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Année de création</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">2004</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">2015</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">2020</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Langages supportés</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Java, Python, C#, JavaScript, Ruby, etc.</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">JavaScript/TypeScript uniquement</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">JavaScript, Python, Java, C#</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Navigateurs</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Chrome, Firefox, Safari, Edge, IE</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Chrome, Firefox, Edge (limité)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Chrome, Firefox, Safari, Edge</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Architecture</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">WebDriver (hors navigateur)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Exécution dans le navigateur</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Protocole DevTools (hors navigateur)</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Vitesse</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Moyenne</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Rapide</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Très rapide</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Installation</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Complexe (drivers requis)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Simple (npm)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Simple (npm, auto-installation)</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Tests parallèles</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Oui (avec configuration)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Payant (Cypress Cloud)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Natif et gratuit</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Multi-onglets/fenêtre</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Oui</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Non</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Oui</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Attente automatique</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Non (explicite requise)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Oui</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Oui</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Débogage</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Difficile</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Excellent (time-travel)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Excellent (traces, vidéos)</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>API testing</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Non natif</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Oui</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Oui</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Mobile</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Oui (avec Appium)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Non</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Oui (émulation)</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Communauté</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Très large (mature)</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Grande et active</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Croissante rapidement</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Critère"><strong>Courbe d'apprentissage</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Selenium">Élevée</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Cypress">Moyenne</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Playwright">Moyenne</td></tr></tbody></table></div>
    <p><strong>Recommandation</strong> : Playwright pour les nouveaux projets (moderne, complet), Cypress pour la simplicité JavaScript, Selenium pour les projets legacy ou multi-langages établis.</p></div>
</details>

### 🔸Appium

<details>
    <summary>Qu'est-ce que Appium ?</summary>
    <p>Appium est un outil open-source permettant d’automatiser les tests mobiles Android et iOS, natifs, hybrides et web.</p>
</details>

<details>
    <summary>Pourquoi choisir Appium ?</summary>
    <ul>
        <li>Cross-platform</li>
        <li>Même code pour Android & iOS</li>
        <li>Support multi-langages</li>
        <li>Compatible CI/CD</li>
    </ul>
</details>

<details>
    <summary>Architecture Appium ?</summary>
    <ul>
        <li>1.  **Client --> Serveur Appium:** Requête HTTP (JSON)</li>
        <li>2.  **Serveur Appium --> Appareil/Simulateur:** Commandes natives</li>
        <li>3.  **Appareil/Simulateur --> Serveur Appium:** Réponse (JSON)</li>
        <li>4.  **Serveur Appium --> Client:** Réponse (JSON)</li>
    </ul>
</details>

### 🔸CI / CD

<details>
    <summary>Qu'est que CI/CD ?</summary>
    <div class="c+qhpcvP6H3VCSU9BgHRlQ=="><table class="zxqV+AyRUca+MLhV37xZ3A=="><thead class="vws+0UuF+kO6CYMvFHvtZQ=="><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><th class="Twce1OmS+ZcG-oo8+adRMg==">Caractéristique</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Intégration continue (CI)</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Déploiement continu (CD)</th><th class="Twce1OmS+ZcG-oo8+adRMg==">Continuous Deployment</th></tr></thead><tbody class="o4qKFCTY3cX9YjCR2ocmKA=="><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Objectif</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Integration (CI)">Intégration fréquente du code</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Delivery (CD)">Automatisation de la mise à disposition</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Deployment">Automatisation du déploiement en production</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Automatisation</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Integration (CI)">Tests unitaires, tests d'intégration</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Delivery (CD)">Déploiement en environnement de test/pré-production</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Deployment">Déploiement en production</td></tr><tr class="_2ebVTgiBfkHr-I+WBkJGUw=="><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Caractéristique"><strong>Intervention humaine</strong></td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Integration (CI)">Minimale</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Delivery (CD)">Possible pour le déploiement final</td><td class="Lj1YMIu6HckHEepSU13LHg==" data-label="Continuous Deployment">Nulle</td></tr></tbody></table></div>
</details>

<details>
    <summary>Outils CI/CD ?</summary>
    <ul>
        <li>Jenkins</li>
        <li>GitLab CI/CD</li>
        <li>GitHub Actions</li>
        <li>CircleCI</li>
        <li>Travis CI</li>
        <li>Azure DevOps</li>
        <li>AWS CodePipeline</li>
    </ul>
</details>

<details>
    <summary>Appium en CI/CD ?</summary>
    <ul>
        <li>Exécution automatique des tests mobiles</li>
        <li>Génération de rapports</li>
        <li>Détection rapide des régressions</li>
    </ul>
</details>

## 🌐API

<details>
    <summary>Qu'est-ce qu'une API ?</summary>
    <p>Une API permet à deux systèmes de communiquer via HTTP (GET, POST, PUT, DELETE).</p>
</details>

<details>
    <summary>Quels types de tests faire sur une API ?</summary>
    <ul>
        <li>Tests fonctionnels</li>
        <li>Tests de statut HTTP</li>
        <li>Tests de sécurité</li>
        <li>Tests de performance</li>
        <li>Tests de validation des données (JSON)</li>
    </ul>
</details>

<details>
    <summary>Différence entre GET / POST ?</summary>
    <p><strong>GET</strong></p>
    <ul>
        <li><strong>Usage</strong> : Récupérer des données depuis le serveur</li>
        <li><strong>Paramètres</strong> : Passés dans l'URL (?param1=valeur1&param2=valeur2)</li>
        <li><strong>Visibilité</strong> : Les données sont visibles dans l'URL (historique, logs)</li>
        <li><strong>Mise en cache</strong> : Peut être mis en cache par le navigateur</li>
        <li><strong>Sécurité</strong> : Ne jamais utiliser pour des données sensibles (mots de passe)</li>
        <li><strong>Idempotent</strong> : Appels multiples = même résultat, sans effet de bord</li>
    </ul>
    <p><strong>POST</strong></p>
    <ul>
        <li><strong>Usage</strong> : Envoyer des données au serveur (créer, modifier)</li>
        <li><strong>Paramètres</strong> : Passés dans le corps de la requête (body)</li>
        <li><strong>Visibilité</strong> : Les données ne sont pas visibles dans l'URL</li>
        <li><strong>Mise en cache</strong> : Généralement pas mis en cache</li>
        <li><strong>Sécurité</strong> : Adapté pour les données sensibles (avec HTTPS)</li>
        <li><strong>Non-idempotent</strong> : Peut créer des ressources à chaque appel</li>
    </ul>
</details>

<details>
    <summary>Outils API ?</summary>
    <p>Postman, Swagger</p>
</details>

## 📒Autres

<details>
    <summary>En informatique, que signifie 'comprendre le métier' ? Quelle attitude adopter en tant que QA ?</summary>
        <p>En informatique, le terme "métier" fait référence aux activités, processus et règles spécifiques d'un domaine professionnel ou d'une entreprise.</p>
        <p>On parle souvent de :</p>  
        <strong>Règles métier :</strong> les contraintes et conditions spécifiques au domaine d'activité      
        <strong>Analyste métier :</strong> un professionnel qui comprend les besoins de l'entreprise et fait le lien avec les développeurs<br>
        <strong>Application métier :</strong> un logiciel conçu pour répondre aux besoins spécifiques d'une activité professionnelle (comptabilité, gestion RH, etc.)<br><br/>  
        Exemple concret : Dans une banque, le "métier" inclut les règles de calcul d'intérêts, les conditions d'octroi de crédit, les processus de virement, etc. Les développeurs doivent traduire ces règles métier en code informatique.
        C'est donc le "quoi" (ce que fait l'entreprise) par opposition au "comment" (la technologie utilisée pour le faire).<br/>
        Un bon QA se doit de comprendre le métier et ne se limite pas aux specs ou un story mapping. Plongez dans le besoin business, challengez les user stories et mettez-vous à la place des utilisateurs finaux.
</details>

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

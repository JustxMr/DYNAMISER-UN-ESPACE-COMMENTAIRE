Voici les documentations utilisé : 'https://developer.mozilla.org/fr/docs/Web/API/Document', 'https://developer.mozilla.org/fr/docs/Web/API/Document/getElementsByClassName'
        'https://developer.mozilla.org/fr/docs/Glossary/DOM', 'https://developer.mozilla.org/fr/docs/Learn_web_development/Getting_started/Your_first_website/Adding_interactivity';

Après quelques recherches supplémentaires et une relecture du code j'ai vite compris mon erreur avec 'getElementsByClassName', je n'ai pas spécifier l'index a l'élément souhaiter, ou bien j'aurais du modifier le code.
J'ai donc utilisé la syntaxe 'getElementByID', documentation : 'https://developer.mozilla.org/fr/docs/Web/API/Document/getElementById'.

Après avoir appercu que le message d'erreur ne se supprimer pas j'ai donc decider de me documenter sur le sujet.

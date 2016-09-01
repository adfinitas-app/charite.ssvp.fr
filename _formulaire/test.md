---
event_woopra: Formulaire de test
panneau_introduction:
  fond_image_path:
  fond_color:
  texte_html:
panneau_question:
  fond_image_path:
  fond_color:
  texte_html:
  champs:
    - type: champ_libre_court
      nom_machine: phone
      reponses:
        - valeur:
      options:
        propriete_visiteur: false
        label:
        placeholder:
        requis: false
        message_erreur:
        controle:
        fond_image_path:
        fond_color:
panneau_informations_personnelles:
  fond_image_path:
  fond_color:
  texte_html:
  champs:
    - type: champ_libre_court
      nom_machine: phone2
      reponses:
        - valeur:
      options:
        propriete_visiteur: false
        label:
        placeholder:
        requis: false
        message_erreur:
        controle:
        fond_image_path:
        fond_color:
options:
  champs_caches:
    - nom:
      valeur:
      propriete_visiteur: false
  bouton_de_soumission: Envoyer
  page_de_remerciement_path: /index.html
_comments:
  nom: Obligatoire et unique. Description courte du champ
  texte: Ce champ peut etre vide
  placeholder: 'Seulement pour les champs de type "champ libre"'
  controle: 'Seulement pour les champs de type "champ libre"'
  reponses: 'Seulement pour les champs de type "choix"'
  page_de_remerciement_path: "URL de la page lorsque l'utilisateur valide le formulaire"
  propriete_visiteur: Cocher cette case si vous souhaitez que ce champs remonte dans les propriété du visiteur sur Woopra
  event_woopra: "Nom de l'evenement sur Woopra qui stockera les répondants <a href=\"http://google.com\" target=\"_blank\">blabla</a>"
  fond_image_path: Image de fond du champ
---

<div class="row">
  <div class="large-12 columns">
    <h1>adfinitas.cx - {{ page.title }}</h1>
  </div>
</div>

{% include form.html %}
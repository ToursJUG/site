---
title: "{{ lower .Name | urlize  }}" # Id de l'after d'une conférence - Id qui sera utilisé sous sa forme urlize pour être affiché dans la page d'une conférence au niveau de la section after (la page de conférence devra alimenter le champ after avec cet id urlizé)
date: {{ .Date }} # date d'ajout
# afterTitle: "" # Titre de la section after, si non défini, cela sera "After"
---

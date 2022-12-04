---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
# description: "" # Description courte du speaker si besoin
date: {{ .Date }} # date d'ajout du speaker
link: "{{ lower (replace (replace (replace (replace .TranslationBaseName "-" "") "é" "e") "è" "e") "ç" "c") }}"
# site: "" # url du blog ou site du speaker
# twitter: "" # url ou id du fil twitter
# github: "" # id de l'utilisateur github
# linkedin: "" # url du profil linkedin
---
---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
# description: "" # Description courte du sponsor si besoin
weight: 9
date: {{ .Date }} # date d'ajout du speaker
link: "{{ lower (replace (replace (replace (replace .TranslationBaseName "-" "") "é" "e") "è" "e") "ç" "c") }}"
# datedebut: "" # Date de début su sponsoring
# datefin: "" # Date de fin su sponsoring
# site: "" # url du site du sponsor
# twitter: "" # url ou id du fil twitter du sponsot
# image: "" # Nom du fichier image contenant le logo du sponsor
---

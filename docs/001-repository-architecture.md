# Repository Architecture

## Purpose

Repozytorium AI Learning OS zostało zaprojektowane jako długoterminowy system zarządzania wiedzą, nauką i projektami związanymi z AI Engineering.

Każdy katalog ma jedną odpowiedzialność (Single Responsibility Principle).

---

# Repository Structure

```
AI-Learning-OS
│
├── docs/
├── knowledge/
├── learning/
├── labs/
├── projects/
├── playbooks/
├── cheatsheets/
├── prompts/
├── resources/
├── templates/
├── decisions/
└── assets/
```

---

# Responsibilities

## docs

Dokumentacja projektu.

Przykłady:

* Project Charter
* Repository Architecture
* Roadmap
* AI State
* Backlog

---

## knowledge

Docelowa baza wiedzy.

Tutaj znajdują się uporządkowane informacje o pojęciach i technologiach.

Przykłady:

* Tokens
* LLM
* MCP
* RAG
* Embeddings
* Agents

---

## learning

Historia procesu nauki.

Każda lekcja zawiera:

* cel,
* teorię,
* ćwiczenia,
* pytania,
* podsumowanie.

Lekcje opisują proces nauki, a nie dokumentację wiedzy.

---

## labs

Eksperymenty.

Tutaj sprawdzamy zachowanie modeli, promptów i różnych ustawień.

Każdy eksperyment powinien zakończyć się wnioskami.

---

## projects

Kod źródłowy.

Każdy większy projekt AI posiada własny katalog.

---

## playbooks

Instrukcje wykonywania konkretnych zadań.

Przykłady:

* Jak wybrać model?
* Jak zaprojektować prompt?
* Jak policzyć koszt tokenów?
* Jak zbudować RAG?

---

## cheatsheets

Szybkie materiały referencyjne.

Przeznaczone do codziennego użytku.

---

## prompts

Biblioteka własnych promptów wraz z opisem ich zastosowania.

Każdy prompt powinien zawierać:

* cel,
* opis,
* przykład,
* ograniczenia,
* modele, z którymi został przetestowany.

---

## resources

Materiały zewnętrzne:

* książki,
* artykuły,
* kursy,
* podcasty,
* filmy.

---

## templates

Szablony dokumentów.

Przykłady:

* Lesson Template
* Knowledge Template
* Prompt Template
* Experiment Template

---

## decisions

Najważniejsze decyzje projektowe.

Każda decyzja posiada uzasadnienie.

Repozytorium powinno umożliwiać zrozumienie, dlaczego określone rozwiązania zostały przyjęte.

---

## assets

Grafiki, diagramy oraz materiały wykorzystywane w dokumentacji.

---

# Information Flow

Nowa wiedza przechodzi przez następujące etapy:

1. Lekcja (`learning`)
2. Eksperyment (`labs`)
3. Uporządkowanie wiedzy (`knowledge`)
4. Zastosowanie w projekcie (`projects`)
5. Utrwalenie w Playbookach i Cheat Sheetach

Każdy etap rozwija poprzedni i pozostawia trwały ślad w repozytorium.

---

# Repository Principles

* Jeden katalog = jedna odpowiedzialność.
* Nie przechowujemy tej samej wiedzy w kilku miejscach.
* Lekcja nie zastępuje dokumentacji.
* Eksperyment zawsze kończy się wnioskami.
* Dokumentacja jest stale rozwijana.
* Repozytorium ma być użyteczne również po zakończeniu nauki.

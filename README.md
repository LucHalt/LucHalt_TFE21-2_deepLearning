# Prüfungsleistung in "Digitale Bildverarbeitung und Mustererkennung"

Dieses Repository beinhaltet die Dokumentation, den Quellcode und alle mitgeltenden Unterlagen.

## Autor

- Name:     Tim Lucas Halt
- MatrNr.:  6682645

## MNIST-Untersuchungen

Dieses Repository beinhaltet Untersuchungen anhand zweier DatensÃ¤tze - MNIST und TinySchiller - in zwei Hauptabschnitten.

## MNIST-Untersuchungen
Der erste Teil dieses Projekts umfasst Experimente mit dem MNIST-Datensatz. Das Hauptziel war die Maximierung der Genauigkeit. Der Prozess wurde in mehreren Schritten durchgefÃ¼hrt, beginnend mit der Verwendung eines Basisnetzes (\autoref{basis}), um den Accuracy-Benchmark festzulegen. 

### Automatisierte Experimente mit Weights & Biases
Um die Untersuchungen am MNIST-Datensatz teilautomatisiert durchzufÃ¼hren, wurde Weights & Biases als Hauptwerkzeug verwendet. Dieses Tool ermöglicht automatische Sweeps fÃ¼r Hyperparameter-Optimierung (\href{https://docs.wandb.ai/guides/sweeps}{Link zu Weights & Biases Dokumentation}). Die Ergebnisse dieser Optimierung und die Details dazu sind in \autoref{sec:wandb} ausfÃ¼hrlich beschrieben.

### Verbesserungen am Modell
Das Training wurde weiter verbessert durch die Integration von Callbacks, die Implementierung von Data-Augmentation und Optimierungen in der Layer-Struktur.

## Experimente mit dem TinySchiller-Datensatz
Der zweite Teil dieses Projekts konzentriert sich auf Experimente mit dem TinySchiller-Datensatz. Dies beinhaltet Versuche zur Reduzierung der Labelanzahl, Parameter und eine umfassende Dokumentation, die Einblicke in diese spezifischen Experimente bietet.

## Anleitung zur Nutzung dieses Repositories
Um die durchgefÃ¼hrten Experimente nachzuvollziehen oder weiterzuentwickeln, folgen Sie bitte den Anweisungen in den jeweiligen Abschnitten der README und den Verweisen auf das verwendete Tool Weights & Biases.

## Verwendete Ressourcen und Plattformen
Für die Berechnungen wurden GPU-Ressourcen von Kaggle und Colab genutzt, um eine effiziente Ausführung der Experimente zu gewÃ¤hrleisten.

! Bitte beachten Sie, dass die vollstÃ¤ndige Dokumentation der Experimente und deren Ergebnisse in den entsprechenden Abschnitten zu finden sind.

? Falls Fragen auftauchen oder Interesse an weiteren Details besteht, kontaktieren Sie uns gerne.

## Einkaufsliste
- [x] Milch
    - [x] Eier
        - [x] Butter
- [ ] Brot

![schönes Bild](schiller.jpg)

---
tags: 
aliases:
  - Diskrete Fourier Transformation
  - IDFT
  - Synthesegleichung
  - Analysegleichung
created: 27. Dezember 2023
source:
  - Laurenz Hölzl
  - Daniel Ch. v. Grüningen
---

# Diskrete [Fourier Transformation](../../Mathe/mathe%20(4)/Fourier%20Transformation.md)

> [!INFO]
> Tatsächlich handelt es sich bei der Diskreten [Fourier Transformation](../../Mathe/mathe%20(4)/Fourier%20Transformation.md) (DFT) um eine Annäherung der [Fourier Transformation](../../Mathe/mathe%20(4)/Fourier%20Transformation.md), welche es ermöglicht sie effizient von einem digitalen Rechner berechnen zu lassen.
Hierbei wird die Formel für die [Fouriertransformierte](../../Mathe/mathe%20(4)/Fourier%20Transformation.md#Fouriertransformierte) als Ausgangspunkt genutzt.

Das zeitkontinuierliche Signal wird durch seinen Abtastwert $x(nT)$ und das Differential durch das Abtastintervall $T$ ersetzt. Zur Annäherung des Integrals wird die Summe verwendet:

$$
X_{s}(\omega) = \sum^{\infty}_{n = -\infty} = x(nT)\cdot e^{-j\omega nT} \cdot T 
$$

Da eine unendliche Anzahl an Abtastwerten unmöglich zu berechnen ist, werden eine endliche Anzahl $N$ dieser herausgeschnitten/„gefenstert“ (engl: windowing).
Außerdem kann der Faktor $T$ aus „Bequemlichkeit“ weggelassen werden.

$$
X_{sw}(f) = \sum^{N-1}_{n=0} x(nT) \cdot e^{-j\omega n \frac{f}{f_{s}}}
$$

Dies [Funktion](../../Mathe/Abbild.md) ist $f_{s}$-periodisch und hat nur an $N$-Stellen linear unabhängige Funktionswerte. Ausgewertet wird sie an $N$ gleichweit entfernten Frequenzstellen $f= \{0, \frac{f_{s}}{N}, 2\cdot\frac{f_{s}}{N}, \dots,(N-1)\frac{f_{s}}{N}\}$.
Werden der Einfachheit halber wieder einige Faktoren ($\frac{f_{s}}{N}, T$) und die Kennzeichnung $sw$ weggelassen ergibt sich die Definition (Analysegleichung) der DFT:

> [!hint] Analysegleichung

Die inverse DFT (IDFT) (Synthesegleichung) ist definiert als:

> [!hint] Synthesegleichung


# Quellen

Yes. Based on your previous context, I understand the target machine is:

* ASUS SonicMaster laptop
* Intel Core i5 10th Gen
* 8 GB RAM
* Windows 11
* Mechanical HDD (not SSD)

This is not a normal optimization task. The goal is to transform it into a stable AI Agent node that can run continuously while maximizing HDD performance and responsiveness.

Below is the engineering context I would load for an AI agent working on that PC.

⸻

AI Agent Context

Role

You are a Senior Computer Engineer specializing in

* Windows Internals
* Storage Systems
* NTFS
* HDD Optimization
* Hardware Diagnostics
* Power Management
* Kernel Performance
* Memory Optimization
* AI Workstation Engineering

Objective:

Transform an HDD-based Windows 11 laptop into the fastest, most stable platform possible without replacing hardware.

The optimization must preserve data integrity while maximizing responsiveness.

⸻

Primary Goals

Priority order

1. Detect hardware bottlenecks
2. Verify HDD health
3. Reduce unnecessary disk activity
4. Reduce RAM pressure
5. Reduce pagefile usage
6. Reduce startup latency
7. Optimize NTFS
8. Optimize Windows services
9. Optimize AI workload execution
10. Maintain long-term HDD health

⸻

Hardware Investigation

Collect

CPU

* Clock speeds
* Thermal throttling
* C states

RAM

* Speed
* Dual/Single channel
* Memory usage
* Compression

Storage

* SMART values
* Reallocated sectors
* Pending sectors
* Read errors
* Write errors
* Transfer mode
* SATA mode
* NCQ support

Motherboard

* AHCI enabled
* BIOS version

Power

* Battery wear
* Current power plan

⸻

HDD Diagnostics

Measure

Sequential Read

Sequential Write

Random Read 4K

Random Write 4K

Average latency

Maximum latency

Queue depth

Fragmentation %

Free space %

SMART temperature

Spin-up time

Seek error rate

⸻

Detect Hidden Problems

Search for

Failing HDD

Bad sectors

Corrupted NTFS

Windows corruption

Driver issues

Storage controller issues

Old Intel RST driver

PIO mode

Background malware

Broken scheduled tasks

Windows indexing overload

OneDrive loops

Defender excessive scanning

Update loops

Corrupted Event Logs

High interrupt usage

⸻

HDD Optimizations

Run

CHKDSK

DISM

SFC

Optimize Drives

Defragment

Trim if SSD detected

Repair NTFS

Repair MFT

Repair USN journal

Rebuild Search Index

Clear Temp

Clear SoftwareDistribution

Clear Windows Update cache

Clear Prefetch corruption

Rebuild icon cache

Rebuild thumbnail cache

Empty recycle bin

Remove old logs

Clean WinSxS

Compact OS if useful

⸻

Windows Services Optimization

Evaluate every service.

Examples

SysMain

Windows Search

Xbox Services

Fax

Print Spooler

Remote Registry

Telemetry

Connected User Experiences

Maps

Retail Demo

Bluetooth if unused

Hyper-V if unused

Touch Keyboard

Windows Insider

Delivery Optimization

Each service should be classified

Essential

Optional

Disable

Never disable

Windows Audio

RPC

Task Scheduler

Plug and Play

Windows Installer

Windows Management Instrumentation

⸻

Startup Optimization

Inspect

Registry Run keys

Startup folder

Task Scheduler

Autoruns

Services

Drivers

Background Updaters

Disable

Adobe

Discord

Steam

Epic

Teams

OneDrive

Widgets

Copilot

Phone Link

OEM software

unless required.

⸻

Memory Optimization

Reduce

Commit charge

Working set

Memory compression overhead

Standby list pressure

Page faults

Pagefile thrashing

Identify memory leaks

Recommend

RAM upgrade path

16 GB preferred

Dual-channel preferred

⸻

Virtual Memory

Analyze

Pagefile size

Disk contention

Peak commit

Recommend

System managed

or

Custom fixed size

depending on workload.

⸻

AI Workload Optimization

Prioritize

CPU availability

RAM availability

Disk cache efficiency

Sequential IO

Avoid random writes

Move temporary AI data

Batch writes

Enable write caching

Minimize swap

Reduce browser tabs

Pin agent priority

⸻

Registry Optimization

Inspect

Explorer

File cache

Menu delays

NTFS timestamps

Startup delay

Power throttling

Game mode interference

Storage policies

Never use unsafe registry tweaks.

⸻

File System Optimization

Evaluate

8.3 names

Last access timestamps

NTFS compression

Directory indexing

Fragmentation

Large file placement

MFT reservation

USN Journal size

⸻

Power Optimization

Enable

Ultimate Performance

or

High Performance

Disable

USB selective suspend

PCIe Link State Power Management

Hard disk sleep

CPU parking

Aggressive power saving

⸻

Driver Optimization

Update

Intel Chipset

Intel ME

Intel Storage

GPU

Network

Audio

BIOS if stable

⸻

Security Optimization

Run

Offline Defender scan

Rootkit detection

Autoruns verification

Unsigned drivers

Persistent scheduled tasks

Suspicious WMI events

⸻

Browser Optimization

Reduce

Extensions

Background execution

Startup preload

Hardware acceleration testing

Tab sleeping configuration

⸻

Monitoring

Create dashboard reporting

CPU

RAM

Disk %

Disk queue length

Disk latency

Read speed

Write speed

Temperature

SMART alerts

Network

Processes

Agent health

⸻

AI Agent Decision Logic

If

Disk active time >90%

AND

Transfer rate <5 MB/s

Then

Identify blocking process

Analyze queue

Suspend offender

Notify user

⸻

If

Available RAM <1 GB

Reduce background tasks

Free standby memory

Delay AI workload

⸻

If

SMART pending sectors >0

Raise critical warning

Recommend immediate backup

⸻

If

Average HDD latency >50 ms

Investigate

Defragmentation

Background writes

Failing drive

⸻

If

Windows corruption detected

Run

DISM

SFC

CHKDSK

⸻

Reporting Format

Every optimization should produce

Current state

Problem

Risk level

Recommended fix

Expected performance gain

Reboot required

Rollback method

⸻

Safety Rules

Never disable critical Windows services.

Never delete user files.

Never force registry edits without backup.

Never optimize if SMART indicates imminent HDD failure.

Always validate results after each change.

Always measure before and after.

⸻

My recommendation for this specific laptop

Given your hardware, I estimate the performance bottleneck distribution to be approximately:

* HDD: 75–85% of the slowdown
* 8 GB RAM (causing paging to the HDD): 10–20%
* Windows 11 background activity: 5–10%

For an AI agent running on this machine, the optimization order should be:

1. Verify HDD health (SMART and surface checks).
2. Eliminate unnecessary disk I/O from startup apps and services.
3. Repair Windows system files and the NTFS file system.
4. Defragment the HDD (if healthy).
5. Tune virtual memory and reduce RAM pressure.
6. Configure a high-performance power plan.
7. Remove OEM bloatware and unnecessary scheduled tasks.
8. Continuously monitor disk queue length, latency, and SMART attributes so the agent can detect degradation early.

If the HDD is healthy, these software optimizations can make the system feel significantly more responsive. If the drive is beginning to fail, no amount of tuning will restore good performance, and replacing it with an SSD would provide by far the largest improvement.
<!-- AlgoRep QCM — 50 Questions Algorithmique Répartie IGL3 FST Tunis El-Manar -->
<!-- Style: Premium Dark Minimalist | Sections: ExMut · Election · Diffusion · Horloges -->
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>AlgoRep QCM — Algorithmique Répartie</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet"/>
<style>
:root{
  --bg:#0a0a0f;--surface:#13131a;--surface2:#1c1c28;--border:#2a2a3d;
  --accent:#7c6fff;--accent2:#ff6b9d;--accent3:#00d4aa;
  --text:#e8e8f0;--text2:#9090b0;--text3:#5a5a7a;
  --correct:#00d4aa;--wrong:#ff4d6d;--neutral:#7c6fff;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:'Inter',sans-serif;min-height:100vh;overflow-x:hidden}

/* HEADER */
.header{background:linear-gradient(135deg,#0d0d1a 0%,#131320 100%);border-bottom:1px solid var(--border);padding:20px 0;position:sticky;top:0;z-index:100;backdrop-filter:blur(20px)}
.header-inner{max-width:900px;margin:0 auto;padding:0 24px;display:flex;align-items:center;justify-content:space-between;gap:16px}
.logo{display:flex;align-items:center;gap:12px}
.logo-icon{width:40px;height:40px;background:linear-gradient(135deg,var(--accent),var(--accent2));border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:18px}
.logo-text{font-size:16px;font-weight:700;letter-spacing:-.3px}
.logo-sub{font-size:11px;color:var(--text2);font-weight:400}
.header-stats{display:flex;gap:20px;align-items:center}
.stat-pill{background:var(--surface2);border:1px solid var(--border);border-radius:20px;padding:6px 14px;font-size:12px;font-weight:500;color:var(--text2)}
.stat-pill span{color:var(--accent);font-weight:700}

/* PROGRESS */
.progress-wrap{max-width:900px;margin:0 auto;padding:16px 24px 0}
.progress-bar-bg{height:4px;background:var(--surface2);border-radius:2px;overflow:hidden}
.progress-bar-fill{height:100%;background:linear-gradient(90deg,var(--accent),var(--accent2));border-radius:2px;transition:width .4s cubic-bezier(.4,0,.2,1);width:0%}
.progress-labels{display:flex;justify-content:space-between;margin-top:6px;font-size:11px;color:var(--text3)}

/* MAIN */
.main{max-width:900px;margin:0 auto;padding:32px 24px 80px}

/* CATEGORY BADGE */
.cat-badge{display:inline-flex;align-items:center;gap:6px;background:var(--surface2);border:1px solid var(--border);border-radius:20px;padding:4px 12px;font-size:11px;font-weight:500;color:var(--text2);margin-bottom:20px;letter-spacing:.5px;text-transform:uppercase}
.cat-dot{width:6px;height:6px;border-radius:50%;background:var(--accent)}

/* QUESTION CARD */
.question-card{background:var(--surface);border:1px solid var(--border);border-radius:20px;padding:32px;margin-bottom:16px;transition:border-color .2s;display:none}
.question-card.active{display:block;animation:fadeUp .3s ease}
@keyframes fadeUp{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
.question-card:hover{border-color:var(--accent);box-shadow:0 0 0 1px var(--accent)20}
.q-number{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--text3);margin-bottom:12px;letter-spacing:1px}
.q-text{font-size:16px;font-weight:500;line-height:1.65;color:var(--text);margin-bottom:28px}
.q-text code{font-family:'JetBrains Mono',monospace;background:var(--surface2);border:1px solid var(--border);border-radius:4px;padding:1px 6px;font-size:13px;color:var(--accent3)}

/* OPTIONS */
.options{display:flex;flex-direction:column;gap:10px}
.opt{display:flex;align-items:flex-start;gap:14px;background:var(--surface2);border:1.5px solid var(--border);border-radius:12px;padding:14px 18px;cursor:pointer;transition:all .2s;position:relative;overflow:hidden}
.opt::before{content:'';position:absolute;inset:0;background:var(--accent);opacity:0;transition:opacity .2s}
.opt:hover::before{opacity:.04}
.opt:hover{border-color:var(--accent);transform:translateX(3px)}
.opt-key{font-family:'JetBrains Mono',monospace;font-size:12px;font-weight:700;color:var(--text3);min-width:20px;padding-top:1px;transition:color .2s}
.opt-text{font-size:14px;line-height:1.55;color:var(--text2);transition:color .2s;position:relative;z-index:1}
.opt:hover .opt-key,.opt:hover .opt-text{color:var(--text)}

/* STATES */
.opt.selected{border-color:var(--accent);background:linear-gradient(90deg,#7c6fff12,var(--surface2))}
.opt.selected .opt-key{color:var(--accent)}
.opt.selected .opt-text{color:var(--text)}
.opt.correct{border-color:var(--correct)!important;background:linear-gradient(90deg,#00d4aa15,var(--surface2))!important}
.opt.correct .opt-key{color:var(--correct)!important}
.opt.wrong{border-color:var(--wrong)!important;background:linear-gradient(90deg,#ff4d6d15,var(--surface2))!important}
.opt.wrong .opt-key{color:var(--wrong)!important}
.opt.disabled{cursor:default;pointer-events:none}

/* EXPLANATION */
.explanation{margin-top:20px;padding:16px 18px;background:var(--surface2);border-left:3px solid var(--accent3);border-radius:0 10px 10px 0;font-size:13px;color:var(--text2);line-height:1.65;display:none}
.explanation.show{display:block;animation:fadeUp .25s ease}
.explanation strong{color:var(--accent3)}

/* NAV BUTTONS */
.nav-row{display:flex;gap:12px;margin-top:28px;align-items:center}
.btn{padding:12px 28px;border-radius:10px;border:none;cursor:pointer;font-size:14px;font-weight:600;font-family:'Inter',sans-serif;transition:all .2s}
.btn-primary{background:linear-gradient(135deg,var(--accent),#5a4fcf);color:#fff}
.btn-primary:hover{transform:translateY(-2px);box-shadow:0 8px 24px #7c6fff40}
.btn-secondary{background:var(--surface2);border:1.5px solid var(--border);color:var(--text2)}
.btn-secondary:hover{border-color:var(--accent);color:var(--text)}
.btn:disabled{opacity:.3;cursor:not-allowed;transform:none!important}

/* QUESTION MAP */
.qmap{display:flex;flex-wrap:wrap;gap:8px;margin:24px 0}
.qmap-item{width:36px;height:36px;border-radius:8px;border:1.5px solid var(--border);background:var(--surface2);font-size:12px;font-weight:600;color:var(--text3);display:flex;align-items:center;justify-content:center;cursor:pointer;transition:all .2s}
.qmap-item:hover{border-color:var(--accent);color:var(--accent)}
.qmap-item.answered{background:var(--accent);border-color:var(--accent);color:#fff}
.qmap-item.current{border-color:var(--accent2);color:var(--accent2);box-shadow:0 0 0 2px #ff6b9d30}
.qmap-item.correct-map{background:var(--correct);border-color:var(--correct);color:#fff}
.qmap-item.wrong-map{background:var(--wrong);border-color:var(--wrong);color:#fff}

/* SCORE SCREEN */
.score-screen{display:none;text-align:center;padding:60px 24px}
.score-screen.show{display:block;animation:fadeUp .5s ease}
.score-ring{width:160px;height:160px;margin:0 auto 32px;position:relative}
.score-ring svg{transform:rotate(-90deg)}
.score-ring-text{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center}
.score-pct{font-size:36px;font-weight:700;color:var(--text)}
.score-label{font-size:12px;color:var(--text3)}
.score-title{font-size:24px;font-weight:700;margin-bottom:8px}
.score-sub{font-size:14px;color:var(--text2);margin-bottom:40px}
.score-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;max-width:500px;margin:0 auto 40px}
.score-stat{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:20px}
.score-stat-val{font-size:28px;font-weight:700;margin-bottom:4px}
.score-stat-lab{font-size:12px;color:var(--text2)}

/* INTRO */
.intro{text-align:center;padding:60px 24px}
.intro h1{font-size:32px;font-weight:700;margin-bottom:12px;background:linear-gradient(135deg,var(--text),var(--accent));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.intro p{color:var(--text2);font-size:15px;max-width:560px;margin:0 auto 32px;line-height:1.7}
.intro-chips{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-bottom:40px}
.chip{background:var(--surface2);border:1px solid var(--border);border-radius:20px;padding:6px 16px;font-size:12px;color:var(--text2)}
</style>
</head>
<body>
<div id="app"><!-- JS renders here --></div>
<script>
// ============================================================
// DATA — 50 QCM questions
// ============================================================
const QUESTIONS=[
{cat:"Exclusion Mutuelle",q:"Dans l'algorithme de Lamport, combien de messages sont nécessaires au total pour qu'un processus accède une fois à la SC (avec N processus) ?",opts:["2×(N−1)","N−1","3×(N−1)","4×(N−1)"],ans:2,exp:"Lamport nécessite (N−1) requêtes + (N−1) ACK + (N−1) lib = <strong>3×(N−1)</strong> messages."},
{cat:"Exclusion Mutuelle",q:"Pi peut entrer en SC dans l'algorithme de Lamport si et seulement si :",opts:["Sa requête est en tête de sa file ET il a reçu un ACK de tous les autres avec estampille > la sienne","Sa requête est en tête de sa file ET il a envoyé un lib à tous","Il a reçu un ACK de la majorité des processus","Sa file locale est vide"],ans:0,exp:"Les deux conditions cumulées : <strong>tête de file</strong> + <strong>ACK de tous</strong> (avec estampille supérieure). Si égalité → on compare les numéros de processus."},
{cat:"Exclusion Mutuelle",q:"Dans Lamport, à la réception d'une requête (Req, ti) de Pi, que fait Pj ?",opts:["Il entre en SC immédiatement","Il envoie un ACK à Pi et place la requête dans sa file","Il envoie un lib à Pi","Il ignore la requête si son propre estampille est plus grand"],ans:1,exp:"Pj enregistre la requête dans sa file locale <strong>et</strong> envoie un ACK à Pi — c'est obligatoire quel que soit son état."},
{cat:"Exclusion Mutuelle",q:"Lamport garantit-il l'absence de famine ?",opts:["Oui, grâce à l'ordre strict des estampilles croissantes","Non, un processus peut être indéfiniment prioritaire","Oui, mais seulement si les canaux sont FIFO","Non, car les ACK peuvent se perdre"],ans:0,exp:"Les estampilles croissantes et l'ordre (estampille, pid) garantissent que chaque demandeur devient <strong>tête de file en temps fini</strong> → pas de famine."},
{cat:"Exclusion Mutuelle",q:"Ricart & Agrawala réduit le nombre de messages par rapport à Lamport en :",opts:["Supprimant les requêtes","Fusionnant les ACK et les messages de libération en une seule réponse différée","Utilisant un jeton à la place des acquittements","Limitant les diffusions à un sous-ensemble de processus"],ans:1,exp:"R&A élimine le message <em>lib</em> séparé : la libération se fait en envoyant les <strong>réponses différées</strong>, réduisant à <strong>2(N−1)</strong> messages."},
{cat:"Exclusion Mutuelle",q:"Dans Ricart & Agrawala, Pi diffère sa réponse à la requête de Pj quand :",opts:["L'estampille de Pi < estampille de Pj","Pi est en SC OU (Pi est demandeur ET estampille Pi < estampille Pj)","Pi est toujours au repos","Pi a déjà envoyé un lib"],ans:1,exp:"Pi diffère si : <strong>il est en SC</strong>, OU s'il est aussi demandeur avec une estampille <em>inférieure</em> (il est prioritaire). C'est le piège classique : la plus petite estampille est prioritaire."},
{cat:"Exclusion Mutuelle",q:"Combien de messages R&A sont nécessaires par accès à la SC (N processus) ?",opts:["3×(N−1)","2×(N−1)","N","2×N"],ans:1,exp:"<strong>(N−1) requêtes</strong> envoyées + <strong>(N−1) réponses</strong> reçues = 2×(N−1). Plus efficace que Lamport (3×(N−1))."},
{cat:"Exclusion Mutuelle",q:"Dans la variante jeton de Ricart & Agrawala, que contient le jeton ?",opts:["L'identifiant du dernier détenteur uniquement","Un tableau jeton[i] indiquant le nombre de fois que chaque Pi a accédé à la RSC","La liste des processus en attente","Un bit booléen indiquant si la RSC est libre"],ans:1,exp:"Le jeton transporte un tableau <strong>jeton[j]</strong> = nb d'accès de Pj connus. Permet de décider à qui envoyer le jeton à la libération."},
{cat:"Exclusion Mutuelle",q:"Dans l'algorithme du jeton circulant (Le Lann 77), la topologie utilisée est :",opts:["Un anneau unidirectionnel","Un anneau bidirectionnel","Un graphe complet","Un arbre couvrant"],ans:0,exp:"Le Lann 77 repose sur un <strong>anneau unidirectionnel</strong> — le jeton ne circule que dans un seul sens."},
{cat:"Exclusion Mutuelle",q:"Quel est l'inconvénient majeur du jeton circulant (Le Lann) ?",opts:["Il ne garantit pas la sûreté","Le jeton circule même si aucun site n'est demandeur","Il nécessite 3(N−1) messages par accès","Il ne garantit pas l'équité"],ans:1,exp:"Même sans demandeur actif, le jeton <strong>tourne en permanence</strong> sur l'anneau → échange de messages inutiles."},
{cat:"Exclusion Mutuelle",q:"Si le jeton est perdu dans Le Lann, la solution est :",opts:["Redémarrer tous les processus","Lancer une élection pour désigner un processus qui régénère le jeton","Envoyer un message de détresse à tous","Utiliser un timeout et recréer le jeton localement"],ans:1,exp:"Perte de jeton → <strong>élection</strong> (ex. Bully ou Chang-Roberts) → le nouveau coordinateur régénère un jeton unique."},
{cat:"Exclusion Mutuelle",q:"Quelle propriété garantit qu'il n'y a qu'un seul jeton dans Le Lann ?",opts:["La vivacité","L'équité","L'unicité du jeton (invariant à maintenir)","La sûreté FIFO"],ans:2,exp:"L'<strong>unicité du jeton</strong> est l'invariant central : un seul jeton en circulation à tout moment garantit la sûreté (au plus un en SC)."},
{cat:"Exclusion Mutuelle",q:"Dans R&A version jeton, quand Pi libère la SC, il cherche le prochain destinataire du jeton en parcourant Req à partir de :",opts:["L'indice 0","L'indice i+1 (cycliquement)","L'indice ayant la plus petite estampille","Un indice aléatoire"],ans:1,exp:"Pi parcourt de <strong>(i+1) mod N</strong> cycliquement pour trouver Pj tel que Req[j] > jeton[j], garantissant l'équité circulaire."},
{cat:"Algorithmes d'Élection",q:"L'algorithme du Bully élit :",opts:["Le processus avec l'identifiant le plus petit","Le processus qui initie l'élection en premier","Le processus avec l'identifiant le plus élevé encore actif","Le processus avec le moins de charge"],ans:2,exp:"Bully (La Brute) : les processus à id plus élevé '<em>écrasent</em>' les autres → élu = <strong>id maximum</strong> parmi les processus actifs."},
{cat:"Algorithmes d'Élection",q:"Quelle est la complexité en messages du Bully dans le pire des cas ?",opts:["O(N²)","O(N·log N)","O(N)","O(1)"],ans:0,exp:"Dans le pire cas (le processus à id le plus bas initie), chaque processus envoie des messages à tous ceux d'id supérieur → <strong>O(N²)</strong>."},
{cat:"Algorithmes d'Élection",q:"Dans le Bully, le meilleur cas correspond à :",opts:["Tous les processus initient l'élection simultanément","Le processus à id le plus élevé (N−1) initie l'élection","Le processus voisin du coordinateur initie","Aucun processus ne répond"],ans:1,exp:"Si le processus d'id max initie, il n'a personne à contacter d'id supérieur → se déclare élu directement → <strong>N−1 messages</strong> seulement (annonce ELU)."},
{cat:"Algorithmes d'Élection",q:"Dans l'algorithme de Le Lann (anneau unidirectionnel), quel processus est élu ?",opts:["Celui avec l'id le plus grand","Celui qui initie l'élection en premier","Celui avec l'id le plus petit parmi les initiateurs","Celui avec le moins de voisins"],ans:2,exp:"Le Lann 77 : chaque id circule sur l'anneau. L'initiateur qui reçoit sa propre id <strong>et</strong> a le plus petit id se déclare élu."},
{cat:"Algorithmes d'Élection",q:"Chang & Roberts améliore Le Lann principalement en :",opts:["Élisant le processus d'id minimum","Éteignant les initiateurs dont l'id est inférieur à un id reçu, réduisant le trafic","Utilisant un anneau bidirectionnel","Nécessitant O(N) messages dans tous les cas"],ans:1,exp:"Chang-Roberts : un initiateur qui reçoit un id <strong>plus grand que le sien s'éteint</strong> et ne retransmet que les plus grands → réduit les messages en moyenne à <strong>O(N·log N)</strong>."},
{cat:"Algorithmes d'Élection",q:"Dans Chang & Roberts, quel processus est finalement élu ?",opts:["Le premier à envoyer un message","Celui dont l'id revient à lui-même après avoir circulé","Celui avec l'id minimum","Celui qui reçoit le plus de messages"],ans:1,exp:"Quand un initiateur reçoit <strong>son propre id</strong> qui a survécu à toute la circonférence → il se déclare élu. Élu = <strong>id maximum</strong>."},
{cat:"Algorithmes d'Élection",q:"L'algorithme de Franklin (1982) se distingue par :",opts:["L'utilisation d'un graphe complet","L'envoi de messages dans les deux sens sur un anneau bidirectionnel","L'élection du processus d'id minimum","La complexité O(N²) dans tous les cas"],ans:1,exp:"Franklin utilise un <strong>anneau bidirectionnel</strong> : chaque candidat envoie son id à gauche et à droite, compare avec ses deux voisins — candidat survit si son id est le max local."},
{cat:"Algorithmes d'Élection",q:"Quelle est la complexité moyenne de Chang & Roberts ?",opts:["O(N)","O(N²)","O(N·log N)","O(log N)"],ans:2,exp:"Chang & Roberts : <strong>O(N·log N)</strong> en moyenne, O(N²) dans le pire cas (ids en ordre décroissant sur l'anneau)."},
{cat:"Algorithmes d'Élection",q:"Quelle est l'utilité principale des algorithmes d'élection dans les systèmes répartis ?",opts:["Optimiser le routage des messages","Désigner un coordinateur quand l'ancien tombe en panne","Équilibrer la charge entre processus","Détecter les interblocages"],ans:1,exp:"L'élection sert à <strong>désigner un nouveau leader/coordinateur</strong> (ex. maître BD distribuée, régénérateur de jeton) quand l'ancien est défaillant."},
{cat:"Algorithmes d'Élection",q:"Dans Le Lann, la complexité dans le pire cas est :",opts:["O(N·log N)","O(N²)","O(N)","O(1)"],ans:1,exp:"Le Lann pire cas : O(N²) — si les ids sont en ordre décroissant, chaque id parcourt presque tout l'anneau avant d'être éliminé."},
{cat:"Algorithmes d'Élection",q:"Quelle propriété un algorithme d'élection doit-il garantir ?",opts:["Sûreté uniquement : un seul élu","Vivacité uniquement : toujours un élu en temps fini","Sûreté ET Vivacité","Équité : tous les processus ont la même probabilité d'être élus"],ans:2,exp:"Élection : <strong>Sûreté</strong> (un seul po élu à la fois) + <strong>Vivacité</strong> (un élu est désigné en temps fini). Les deux ensemble."},
{cat:"Diffusion",q:"La différence entre Broadcast et Multicast est :",opts:["Le broadcast est fiable, le multicast ne l'est pas","Le multicast cible un groupe sélectionné, le broadcast cible tous les nœuds du réseau","Le broadcast utilise un arbre, le multicast utilise le flooding","Le multicast garantit l'ordre FIFO, pas le broadcast"],ans:1,exp:"<strong>Broadcast</strong> = tous les nœuds. <strong>Multicast</strong> = groupe sélectionné. L'émetteur peut ne pas appartenir au groupe multicast."},
{cat:"Diffusion",q:"Dans le protocole de diffusion Best-Effort, que se passe-t-il si l'émetteur plante en cours de diffusion ?",opts:["Tous les processus reçoivent quand même le message grâce à la rediffusion","Certains processus peuvent recevoir le message, d'autres non","Le protocole relance automatiquement la diffusion","Aucun processus ne reçoit le message"],ans:1,exp:"Best-Effort : <strong>pas de garantie globale</strong>. Si l'émetteur plante après avoir envoyé à certains seulement → réception partielle possible."},
{cat:"Diffusion",q:"Le Flooding (inondation) présente comme inconvénient principal :",opts:["Il ne peut pas atteindre tous les nœuds","La duplication excessive des messages","Il nécessite un arbre couvrant préalable","Il ne fonctionne que sur anneaux"],ans:1,exp:"Flooding : chaque nœud retransmet à tous ses voisins → <strong>duplication massive</strong> des messages (un même message reçu plusieurs fois par nœud)."},
{cat:"Diffusion",q:"La diffusion par Spanning Tree (arbre couvrant) garantit :",opts:["La tolérance aux pannes de liens","N−1 messages et aucune duplication","L'ordre causal de délivrance","La fiabilité si l'émetteur plante"],ans:1,exp:"Spanning Tree : <strong>N−1 messages exactement</strong> (un par lien de l'arbre), aucune duplication. Inconvénient : sensible aux pannes de liens de l'arbre."},
{cat:"Diffusion",q:"La propriété d'accord (Agreement) dans la diffusion fiable signifie :",opts:["L'émetteur délivre le message avant tous les autres","Si un processus correct reçoit m, alors tous les processus corrects reçoivent m","Les messages sont délivrés dans l'ordre d'émission","Aucun message dupliqué n'est délivré"],ans:1,exp:"Accord = <strong>tout ou rien</strong> pour les processus corrects : si l'un reçoit, tous reçoivent. C'est la garantie clé de la diffusion fiable."},
{cat:"Diffusion",q:"La diffusion fiable garantit-elle un ordre de délivrance des messages ?",opts:["Oui, ordre FIFO toujours garanti","Oui, ordre causal toujours garanti","Non, aucune contrainte d'ordre n'est spécifiée","Oui, ordre total garanti"],ans:2,exp:"La diffusion fiable garantit validité, accord et intégrité — mais <strong>aucun ordre</strong> de délivrance n'est imposé. L'ordre est une propriété additionnelle."},
{cat:"Diffusion",q:"Quelle relation existe entre l'ordre FIFO et l'ordre Causal ?",opts:["FIFO ⊃ Causal (causal est plus fort)","FIFO = Causal (équivalents)","FIFO ⊂ Causal (causal implique FIFO, pas l'inverse)","Ils sont indépendants"],ans:2,exp:"<strong>Causal → FIFO</strong> mais pas l'inverse. L'ordre causal est plus fort : il respecte toutes les relations happened-before, pas seulement l'ordre d'un même émetteur."},
{cat:"Diffusion",q:"La diffusion atomique (ABCAST) est définie comme :",opts:["Diffusion fiable + ordre FIFO","Diffusion fiable + ordre causal","Diffusion fiable + ordre total","Diffusion best-effort + ordre total"],ans:2,exp:"<strong>Diffusion Atomique = Diffusion Fiable + Ordre Total</strong>. Tous les processus corrects délivrent le même ensemble de messages dans le même ordre."},
{cat:"Diffusion",q:"L'ordre Total dans la diffusion signifie :",opts:["Les messages d'un même émetteur sont délivrés dans l'ordre d'envoi","Si Pi délivre m avant m', alors tous les processus corrects délivrent m avant m'","Les messages causalement liés sont délivrés dans l'ordre causal","Chaque message est délivré au plus une fois"],ans:1,exp:"<strong>Ordre Total</strong> = même ordre de délivrance pour <em>tous</em> les processus corrects, indépendamment de l'émetteur."},
{cat:"Diffusion",q:"La diffusion Gossip / Épidémique présente comme avantage principal :",opts:["Garantie de réception par tous les nœuds","Nombre minimal de messages (N−1)","Scalabilité et tolérance aux pannes","Ordre causal garanti"],ans:2,exp:"Gossip est <strong>scalable et tolérant aux pannes</strong>. Inconvénient : probabiliste, pas de garantie absolue de réception par tous."},
{cat:"Diffusion",q:"L'ordre FIFO seul (sans fiabilité) garantit-il que tous les messages sont délivrés ?",opts:["Oui, FIFO implique délivrance garantie","Non, FIFO impose uniquement l'ordre pour un même émetteur, pas la délivrance","Oui, si les canaux sont fiables point-à-point","Non, uniquement si combiné avec l'ordre causal"],ans:1,exp:"<strong>FIFO ≠ Fiable</strong>. FIFO impose que si Pi envoie m puis m', tout processus délivre m avant m' — mais un message peut ne jamais être délivré du tout."},
{cat:"Diffusion",q:"Dans la diffusion causale (CBCAST), si A.d1 précède causalement B.d2, alors :",opts:["B.d2 peut être délivré avant A.d1 sans violation","A.d1 doit être délivré avant B.d2 par tous les processus corrects","L'ordre de délivrance est indéterminé","Seul B doit respecter cet ordre"],ans:1,exp:"Ordre causal : si m1 <em>précède causalement</em> m2, alors <strong>tous les processus corrects délivrent m1 avant m2</strong> — quel que soit l'émetteur."},
{cat:"Diffusion",q:"Quelle combinaison correspond à la diffusion fiable FIFO ?",opts:["Best-effort + ordre total","Fiable + ordre causal","Fiable + ordre FIFO","Fiable + ordre total"],ans:2,exp:"<strong>Diffusion FIFO Fiable = Diffusion Fiable + Ordre FIFO</strong>. Distinct de la causale (qui est plus forte) et de l'atomique (ordre total)."},
{cat:"Diffusion",q:"La diffusion uniforme diffère de la diffusion fiable en ce qu'elle :",opts:["Utilise moins de messages","Impose des contraintes même sur les processus fautifs","Ne garantit que l'accord, pas la validité","Est équivalente à la diffusion fiable"],ans:1,exp:"Diffusion <strong>Uniforme</strong> = les propriétés (accord, etc.) s'appliquent aussi aux processus qui tombent en panne — plus forte que la fiable classique."},
{cat:"Horloges & Causalité",q:"La principale différence entre horloge scalaire de Lamport et horloge vectorielle est :",opts:["L'horloge vectorielle consomme moins de mémoire","L'horloge vectorielle capture la causalité complète (concurrent vs précédent), Lamport seulement l'ordre partiel","L'horloge de Lamport est plus précise","Elles sont équivalentes pour les systèmes répartis"],ans:1,exp:"Lamport → <strong>ordre partiel</strong> (si a→b alors h(a)<h(b) mais l'inverse n'est pas garanti). Vectorielle → <strong>causalité complète</strong> (équivalence avec →)."},
{cat:"Horloges & Causalité",q:"Règle de mise à jour de l'horloge de Lamport lors de la réception d'un message avec horloge h' :",opts:["h = h + 1","h = h' + 1","h = max(h, h') + 1","h = max(h, h')"],ans:2,exp:"Réception : <strong>h = max(h_local, h_reçu) + 1</strong>. Le +1 est crucial et souvent oublié aux examens."},
{cat:"Horloges & Causalité",q:"Si deux événements ont la même horloge de Lamport, ils sont :",opts:["Nécessairement causalement liés","Nécessairement concurrents","Potentiellement concurrents OU causalement liés (impossible de distinguer sans horloge vectorielle)","Forcément sur le même processus"],ans:2,exp:"Lamport ne distingue pas : même estampille peut signifier concurrence OU causalité. Seule l'<strong>horloge vectorielle</strong> permet de trancher."},
{cat:"Horloges & Causalité",q:"Une coupure est cohérente si et seulement si :",opts:["Tous les processus ont le même nombre d'événements dans la coupure","Aucun message n'est reçu dans la coupure sans avoir été émis dans la coupure","Tous les messages en transit sont inclus dans la coupure","La coupure contient exactement N événements"],ans:1,exp:"Cohérence : pas de <em>message zombie</em> — si la réception r est dans la coupure, l'émission correspondante doit aussi l'être. <strong>Pas de message traversant la coupure de droite à gauche.</strong>"},
{cat:"Horloges & Causalité",q:"L'algorithme de Chandy-Lamport sert à :",opts:["Élire un coordinateur dans un système réparti","Capturer un état global cohérent (snapshot) sans arrêter le système","Diffuser un message à tous les processus de façon causale","Détecter les interblocages en temps réel"],ans:1,exp:"Chandy-Lamport = algorithme de <strong>snapshot distribué</strong> : capture un état global cohérent pendant l'exécution normale, via des marqueurs."},
{cat:"Horloges & Causalité",q:"Dans Chandy-Lamport, que fait un processus Pi qui reçoit un marqueur pour la première fois sur un canal Cji ?",opts:["Il ignore le marqueur et continue","Il enregistre son état local, commence à enregistrer les messages entrants sur ses autres canaux, et envoie un marqueur sur tous ses canaux sortants","Il envoie son état à tous les processus","Il s'arrête jusqu'à la fin du snapshot"],ans:1,exp:"Première réception marqueur : <strong>enregistrer état local + enregistrer canaux entrants restants + propager marqueur</strong>. Si marqueur déjà reçu → l'état du canal = messages reçus depuis l'enregistrement jusqu'au marqueur."},
{cat:"Horloges & Causalité",q:"Dans un système réparti, l'absence d'horloge globale implique :",opts:["L'impossibilité d'ordonner les événements","L'utilisation d'horloges logiques pour établir un ordre partiel ou causal","Que tous les algorithmes sont impossibles à implémenter","Que les messages doivent être synchrones"],ans:1,exp:"Sans horloge globale, on utilise des <strong>horloges logiques</strong> (Lamport scalaire ou vectorielle) pour établir un ordre partiel sur les événements."},
{cat:"Pièges & Révision",q:"Lequel de ces énoncés est FAUX concernant R&A ?",opts:["R&A nécessite 2(N−1) messages par accès SC","Dans R&A, le processus avec la plus petite estampille est prioritaire","Dans R&A, un processus au repos répond immédiatement","Dans R&A, un processus en SC diffère sa réponse et envoie un lib séparé à la sortie"],ans:3,exp:"FAUX : dans R&A, à la sortie de SC, Pi envoie les <strong>réponses différées directement</strong> (pas un lib séparé). Il n'y a pas de message lib — c'est la différence clé avec Lamport."},
{cat:"Pièges & Révision",q:"Quelle affirmation est CORRECTE concernant la diffusion atomique ?",opts:["Diffusion atomique = diffusion causale + ordre FIFO","Diffusion atomique = diffusion fiable + ordre total","Diffusion atomique = best-effort + ordre causal","Diffusion atomique = diffusion FIFO + ordre causal"],ans:1,exp:"<strong>Atomique = Fiable + Ordre Total</strong>. Ne pas confondre avec causale (fiable + causal) ou FIFO (fiable + FIFO)."},
{cat:"Pièges & Révision",q:"Si P2 tombe en panne pendant qu'il détient la SC dans Lamport, la conséquence est :",opts:["Les autres processus entrent en SC normalement","Famine : P1 et P3 attendent indéfiniment le lib de P2","P1 et P3 se partagent automatiquement la SC","L'élection d'un nouveau coordinateur est déclenchée automatiquement"],ans:1,exp:"P2 défaillant en SC = <strong>jamais de lib envoyé</strong> → P1 et P3 bloqués indéfiniment = <strong>famine</strong>. Solution : timeout + exclusion de P2 du groupe."},
{cat:"Pièges & Révision",q:"Concernant le Bully et Le Lann, laquelle de ces comparaisons est exacte ?",opts:["Bully élit l'id min, Le Lann élit l'id max","Bully élit l'id max, Le Lann élit l'id min","Tous deux élisent l'id max","Tous deux élisent l'id min"],ans:1,exp:"Piège classique : <strong>Bully → id MAX</strong> (le plus puissant gagne), <strong>Le Lann → id MIN</strong> (le plus petit id circulant sur l'anneau est élu)."},
{cat:"Pièges & Révision",q:"Pourquoi l'idée de partager N places en p lots de N/p dans un algorithme de parking distribué est-elle incorrecte ?",opts:["Car p ne divise pas toujours N","Car si un lot est plein et d'autres sont vides, des voitures sont refusées inutilement — violation de la vivacité","Car cela viole la sûreté en dépassant N","Car les gardiens ne peuvent pas communiquer"],ans:1,exp:"Violation de <strong>vivacité</strong> : une voiture peut être refusée même si le parking global n'est pas plein (son lot local est plein). Sous-utilisation des ressources."},
{cat:"Pièges & Révision",q:"Dans la diffusion causale, un protocole correct gère la violation en :",opts:["Rejetant définitivement le message reçu en avance","Retardant la délivrance du message jusqu'à ce que tous ses prédécesseurs causaux aient été délivrés","Demandant une retransmission à l'émetteur","Délivrant immédiatement puis envoyant une correction"],ans:1,exp:"La diffusion causale <strong>met en attente (bufferise)</strong> m2 jusqu'à ce que m1 (son prédécesseur causal) soit délivré. Garantit l'ordre causal sans rejeter de messages."}
];
// ============================================================
// STATE
// ============================================================
let cur=0,answers=Array(QUESTIONS.length).fill(-1),submitted=Array(QUESTIONS.length).fill(false);
const KEYS=['A','B','C','D'];
const CAT_COLORS={'Exclusion Mutuelle':'#7c6fff',"Algorithmes d'Élection":'#ff6b9d','Diffusion':'#00d4aa','Horloges & Causalité':'#ffd166','Pièges & Révision':'#ff9f43'};
function score(){return answers.reduce((s,a,i)=>s+(a===QUESTIONS[i].ans?1:0),0);}
function pct(){return Math.round(score()/QUESTIONS.length*100);}
function renderHeader(){
  const s=submitted.filter(Boolean).length;
  return `<div class="header"><div class="header-inner"><div class="logo"><div class="logo-icon">⚡</div><div><div class="logo-text">AlgoRep QCM</div><div class="logo-sub">Algorithmique Répartie · IGL3 FST</div></div></div><div class="header-stats"><div class="stat-pill">Question <span>${cur+1}</span>/${QUESTIONS.length}</div><div class="stat-pill">Répondues <span>${s}</span></div><div class="stat-pill">Score <span>${score()}</span></div></div></div><div class="progress-wrap"><div class="progress-bar-bg"><div class="progress-bar-fill" style="width:${(cur+1)/QUESTIONS.length*100}%"></div></div><div class="progress-labels"><span>${QUESTIONS[cur].cat}</span><span>${cur+1} / ${QUESTIONS.length}</span></div></div></div>`;
}
function renderQMap(){
  return `<div class="qmap">${QUESTIONS.map((q,i)=>{let cls='qmap-item';if(i===cur)cls+=' current';else if(submitted[i]){cls+=answers[i]===q.ans?' correct-map':' wrong-map';}else if(answers[i]>=0)cls+=' answered';return `<div class="${cls}" onclick="goTo(${i})">${i+1}</div>`;}).join('')}</div>`;
}
function renderQuestion(){
  const q=QUESTIONS[cur],color=CAT_COLORS[q.cat]||'#7c6fff',isSubmitted=submitted[cur];
  const opts=q.opts.map((o,i)=>{let cls='opt';if(isSubmitted){cls+=' disabled';if(i===q.ans)cls+=' correct';else if(i===answers[cur]&&answers[cur]!==q.ans)cls+=' wrong';}else if(answers[cur]===i)cls+=' selected';return `<div class="${cls}" onclick="select(${i})"><span class="opt-key">${KEYS[i]}</span><span class="opt-text">${o}</span></div>`;}).join('');
  const expHtml=isSubmitted?`<div class="explanation show">💡 ${q.exp}</div>`:'';
  return `<div class="question-card active"><div class="cat-badge"><span class="cat-dot" style="background:${color}"></span>${q.cat}</div><div class="q-number">QUESTION ${String(cur+1).padStart(2,'0')} / ${QUESTIONS.length}</div><div class="q-text">${q.q}</div><div class="options">${opts}</div>${expHtml}<div class="nav-row"><button class="btn btn-secondary" onclick="goTo(${cur-1})" ${cur===0?'disabled':''}>← Précédente</button>${!isSubmitted?`<button class="btn btn-primary" onclick="submit()" ${answers[cur]<0?'disabled':''}>Valider ✓</button>`:''} ${cur<QUESTIONS.length-1?`<button class="btn btn-primary" onclick="goTo(${cur+1})">Suivante →</button>`:`<button class="btn btn-primary" onclick="showScore()">Résultats 🏆</button>`}</div></div>`;
}
function renderScore(){
  const s=score(),p=pct(),emoji=p>=80?'🏆':p>=60?'👍':p>=40?'📚':'💪',msg=p>=80?'Excellent ! Tu maîtrises AlgoRep !':p>=60?'Bon travail, révise les points faibles !':p>=40?'Continue tes révisions !':'Relis le guide et recommence !';
  const r=69,c=2*Math.PI*r,dash=c*(1-p/100);
  return `<div class="score-screen show"><div class="score-ring"><svg width="160" height="160" viewBox="0 0 160 160"><circle cx="80" cy="80" r="${r}" fill="none" stroke="#1c1c28" stroke-width="12"/><circle cx="80" cy="80" r="${r}" fill="none" stroke="url(#gr)" stroke-width="12" stroke-linecap="round" stroke-dasharray="${c.toFixed(2)}" stroke-dashoffset="${dash.toFixed(2)}"/><defs><linearGradient id="gr" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#7c6fff"/><stop offset="100%" stop-color="#ff6b9d"/></linearGradient></defs></svg><div class="score-ring-text"><div class="score-pct">${p}%</div><div class="score-label">Score</div></div></div><div class="score-title">${emoji} ${msg}</div><div class="score-sub">Tu as répondu correctement à <strong style="color:#7c6fff">${s}</strong> questions sur <strong>${QUESTIONS.length}</strong></div><div class="score-grid"><div class="score-stat"><div class="score-stat-val" style="color:#00d4aa">${s}</div><div class="score-stat-lab">✓ Correctes</div></div><div class="score-stat"><div class="score-stat-val" style="color:#ff4d6d">${QUESTIONS.length-s}</div><div class="score-stat-lab">✗ Incorrectes</div></div><div class="score-stat"><div class="score-stat-val" style="color:#7c6fff">${p}%</div><div class="score-stat-lab">Résultat</div></div></div><button class="btn btn-primary" onclick="restart()">🔄 Recommencer</button> <button class="btn btn-secondary" style="margin-left:12px" onclick="goTo(0)">📋 Revoir</button></div>`;
}
function renderIntro(){
  const cats=[...new Set(QUESTIONS.map(q=>q.cat))];
  return `<div class="intro"><h1>Algorithmique Répartie — QCM</h1><p>50 questions couvrant l'intégralité du programme IGL3 FST. Questions tricky — pas de réponse évidente ni de pattern. Testez votre vrai niveau.</p><div class="intro-chips">${cats.map(c=>`<span class="chip" style="border-color:${(CAT_COLORS[c]||'#7c6fff')}40;color:${CAT_COLORS[c]||'#7c6fff'}">${c}</span>`).join('')}<span class="chip">50 Questions</span><span class="chip">Explications</span></div><button class="btn btn-primary" onclick="startQuiz()">Commencer le QCM →</button></div>`;
}
let view='intro';
function startQuiz(){view='quiz';render();}
function select(i){if(!submitted[cur]){answers[cur]=i;render();}}
function submit(){if(answers[cur]>=0){submitted[cur]=true;render();}}
function goTo(i){if(i>=0&&i<QUESTIONS.length){cur=i;render();}}
function showScore(){view='score';render();}
function restart(){cur=0;answers=Array(QUESTIONS.length).fill(-1);submitted=Array(QUESTIONS.length).fill(false);view='intro';render();}
function render(){
  const app=document.getElementById('app');
  if(view==='intro'){app.innerHTML=renderIntro();return;}
  if(view==='score'){app.innerHTML=renderHeader()+`<div class="main">`+renderScore()+`</div>`;return;}
  app.innerHTML=renderHeader()+`<div class="main">`+renderQMap()+renderQuestion()+`</div>`;
}
render();
</script>
</body>
</html>

# hse_hw2_chip

### Ссылка на google colab: https://colab.research.google.com/drive/19GJBfi7sAHjZDg0NtEXVp1z7ZgzqNR4V?usp=sharing

## FastQC-файлы:
Для всех трех образцов файлы получились достаточно хорошими, в том числе, не требуется фильтрация или подрезание чтений, так как всё находится в пределах нормы. Ниже представлены некоторые скриншоты выдачи (полные файлы возможно посмотреть в соответсвующей папке репозитория)

### ENCFF499TDD.fastq
<img width="192" alt="image" src="https://user-images.githubusercontent.com/67833171/156905049-e579ae3c-5f05-4fb3-97a5-3edd01b9e756.png">

<img width="403" alt="image" src="https://user-images.githubusercontent.com/67833171/156905114-fba9bf9a-555f-45d1-b3e3-9c0d1294aa18.png">

<img width="482" alt="image" src="https://user-images.githubusercontent.com/67833171/156905061-5e47b8c5-2e4d-4a12-b541-447bbfb5d57e.png">

<img width="479" alt="image" src="https://user-images.githubusercontent.com/67833171/156905067-660802a1-94c7-4cb0-9d91-c30e4208f8ef.png">

<img width="477" alt="image" src="https://user-images.githubusercontent.com/67833171/156905079-73d472c9-b6da-4a15-a610-6ef4faa55ff9.png">

### ENCFF771RQM.fastq
<img width="178" alt="image" src="https://user-images.githubusercontent.com/67833171/156905229-2aaa011c-b4b5-4324-97d6-ecf0b2da8a0f.png">

<img width="360" alt="image" src="https://user-images.githubusercontent.com/67833171/156905177-3ac9b993-39a5-4b8b-adbd-ae059632e7d2.png">

<img width="473" alt="image" src="https://user-images.githubusercontent.com/67833171/156905197-cd115632-dafa-497e-ab05-fa888971b837.png">

<img width="482" alt="image" src="https://user-images.githubusercontent.com/67833171/156905211-3374a4c2-818d-47f2-b05e-0eb79077d7b6.png">

<img width="482" alt="image" src="https://user-images.githubusercontent.com/67833171/156905217-071aea6a-760f-405f-8ef4-5b9119542792.png">

### ENCFF888OQB.fastq
<img width="203" alt="image" src="https://user-images.githubusercontent.com/67833171/156904999-395df0c6-ffa9-4dba-b841-213bad2ea795.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/67833171/156905168-2ac769bf-4556-4b23-bf62-347437633ffe.png">

<img width="482" alt="image" src="https://user-images.githubusercontent.com/67833171/156904937-736726ff-5359-49cd-a18d-7d9f2d91dda6.png">

<img width="484" alt="image" src="https://user-images.githubusercontent.com/67833171/156905016-bb8b4bcf-f258-4d4f-9b10-4f76743363ef.png">

## Таблица со статистикой по чтениям:
<img width="860" alt="image" src="https://user-images.githubusercontent.com/67833171/156904909-15032b47-cd93-4ee7-a334-3bcd092e113a.png">

## Диаграммы Венна

В данной части задания были построены диаграммы Венна пересечения геномных областей (они показывают количество перекрытия пиками первого образца (первого файла, поступившего на вход команде) пиков второго). Здесь реплики сравнивались с пиками, которые приведены в ENCODE (версия генома hg38). 
Hазличия в количестве пересечений можно объяснить тем, что для получения диаграмм Венна важно, какой образец берется за главный для сравнения. То есть, 
Ниже представлены сначала пересечения первой реплики - ENCFF499TDD.fastq, а затем второй реплики - ENCFF771RQM.fastq.

## Бонус:
**Здесь рассматривается гистоновая метка H3K4me3:**

<img width="440" alt="image" src="https://user-images.githubusercontent.com/67833171/156907252-788aa831-7ff2-42cd-b7f9-71f919374bec.png">

**Для bam файла https://www.encodeproject.org/files/ENCFF889MWV/** 

<img width="439" alt="image" src="https://user-images.githubusercontent.com/67833171/156907284-e7b99316-9dbb-443b-9f9a-04732927f369.png">

<img width="457" alt="image" src="https://user-images.githubusercontent.com/67833171/156907272-d627a50c-7cf5-4958-89ee-f1930edebbb2.png">

**Для bam файла https://www.encodeproject.org/files/ENCFF722HLJ/**

<img width="418" alt="image" src="https://user-images.githubusercontent.com/67833171/156929181-4d1453d3-8d79-4f6c-bf25-b798eaba7f8c.png">

<img width="508" alt="image" src="https://user-images.githubusercontent.com/67833171/156929197-a27d3e4c-2bc5-47ac-9779-d3d833eaefed.png">

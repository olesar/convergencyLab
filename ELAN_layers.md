# ELAN layers 
Annotation of spoken corpora in ConLab

## A preliminary list of labels

```
po@sek1930m          ├ И потом сюда <выехала>.   ┤          ├ Выехала.             ┤  
dt@sek1930m          ├ i pat'om sud'a            ┤          ├ v'yixala             ┤  
mb@sek1930m          ├ i patom suda              ┤          ├ vy-jex-a=l-a         ┤   
 ˪mt@sek1930m                                               ├ prefix-root-suffix=  ┤  
gl@sek1930m          ├and.CONJ then.ADV here.ADV ┤          ├ vy-jex-a-la          ┤  
 ˪word@sek1930m      ├И   ┤├потом┤├сюда          ┤          ├ выехала              ┤                  
 ˪lemma@sek1930m     ├И   ┤├потом┤├сюда          ┤          ├ выехать              ┤             
 ˪pos@sek1930m       ├CONJ┤├ADV  ┤├ADV           ┤          ├ V                    ┤           
 ˪feat@sek1930m      ├    ┤├     ┤├              ┤          ├ PST.3fs              ┤        
tl@sek1930m          ├                           ┤          ├                      ┤               
tf@sek1930m          ├                           ┤          ├                      ┤               
[tn@sek1930m]        ├                           ┤          ├                      ┤               
vb@sek1930m          ├                           ┤├Смеется┤                    
nb@sek1930m          ├                           ┤          ├ Застегивает молнию   ┤               
nt@sek1930m          ├ комментарий               ┤          ├                      ┤   
lg@sek1930m          ├Russian-Ustja          ----┤                                    # or ISO code?
episode              ├Рассказ о жизни                                                                ...┤  
```

```
po@nrd-Interviewer                                                                      ├Да?!  ┤   
...  
```

## Participant-specific tier types  
These are based on L&C ELAN template (template-LandC-v1-explanation.txt) published at https://tla.mpi.nl/tools/tla-tools/elan/thirdparty/:  

`po` (practical orthography)  
`dt` (detailed transcript)  
`mb` (morpheme boundaries)  
`gl` (interlinear gloss)  
`tl` (literal translation, English)  
`tf` (free translation, English)  
`tn` (translation in lingua franca)  
`vb` (visible behaviour)  
  
`mt` (morpheme types): prefix, root
`nb` (non-verbal behaviour)
`nt` (notes)
`lg` (language) -- can be important for code-switching studies

## Tier types not linked to participants

`episode`/`ep` (episodes) -- a title for a part of text, e.g. Сказка о солнце.    

## Tagging participants
The tier names incude @ + 2-3 letters (name, [patronymic,] last name) + year of birth + gender (m/f)  
e.g. @sek1930m  
All letters are latin, for the purposes of conversion/post-processing.

## Questions  

* Как кодировать код-свитчинг? (два слоя?)  
cf. lang@JW in smallExample.eaf
  
* Названия файлов?  
  
* Как помечать интервьюера?  
  
* Пары для нотации латиницей VS в оригинальной орфографии? (могут аннотироваться автоматически, по большей части)

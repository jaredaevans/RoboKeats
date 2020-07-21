# RoboKeats

John Keats was a prolific Romantic poet. Alongside Byron and Shelley, Keats is widely regarded as one of the most influencial figures from the second generation of Romantic poets.  His career was extraordinary, especially considering its brevity - he died from tuberculosis at age 25.  Though he was not well known in his lifetime, his potent prose has inspired generations of others and brought him to deserved fame.  That he produced so much memorable work in his lifetime brings many, including myself, to wonder what he might have achieved if only blessed with more time.  This is my foolhardy attempt to continue his works. :)

### To do:
- Expand corpus:  his letters also consider training on works by Byron or Shelley
- Better attention or transformer

## Embedding + Attention 

Using a deeper LSTM network with attention, this program tries to mimic Keats words from text seeds at the word level.  It does a surprisingly good job of capturing the spirit of his prose. 

 glimmers thy crescent wheresoe'er it be  
 'tis in the breath of heaven thou dost taste  
 freedom as none can taste it nor dost waste  
 thy loveliness in dismal elements  
 but finding in our green earth sweet contents  
 there livest blissfully ah thou was day  
 as list looking and i wept to such  
 ah more sudden impious o'er my store  
 is dying like fair passing in oberon  
 ah for he pass ye wherefore not i can has tell  
 on this sweet dew that hear this sweet jubilee  
 sweet thousand thoughts would never was drear air  

## Embedding-based 

Using a deeper LSTM network and Keats existing work, this program tries to mimic Keats words from text seeds at the word level.  It does a surprisingly good job of capturing the spirit of his prose.  Maybe he needs an editor though?

 an incense delights of summer wings  
 to every half years of this moment grace  
 her on green brow had but so past every dim  
 and once was into her own strange woe  
 when there had ever soft like grief  
 flew the silver seasons was his meek  
 and onward from its summer streams how gone  
 came happy as upon the world they stood  
 old could a tale and never they had gone  
 his long spirit lean upon his hand born  
 and every stars the splendour 'twas the head  
 dost see his own golden spirit it could see  
 
 upon the after deep of trees  
 some green world on a noise wherewith  
 think in thy ear of light moment sleep  
 from aye o themselves for we doth find  
 every lovely sigh of human lovers done  

## Character-based 

Using a simple LSTM network and Keats existing work, this program tries to mimic Keats words from text seeds at the character level

Sample:  
 the first more little shades for since  
 and a feeling soul with side  
 the bright cruel arm charm'd upon  
 and felt he can not charmed  
 on the old than and white dead  
 dear so more in her stars made  
 to her stars of bright again  
 the said great the leaves beauty  
 strive the bright and spread more shade  
 for cares he stood he poor speak of a shade  
 in each faint my day no more closed smile  
 would i strange love sparkling fair and streams  
 the mouth of orge many a wander to string  
 perching my blood with pillow hard muse were there  


With a higher temperature, RoboKeats quickly starts to sound more like Lewis Carroll:  
 o to tawne wrodes had colome at last  
 a deathy whine shadies night and sweet  
 or beened and sthed nest as 'twas know ping and flool  
 rought shelpless enwant from the unlaving lore  
 felt beam roof look robble to the troo'd  
 whene fronted on h it without those mountain  
 save he od aa slumber and said her brightes  
 have in mild and wavy few thy calip  
 thy signon bull once he water unbendless  
 to conuming through a moant forth  
 alas this in the from for her sulser sun  
 tile war on haught and bright winder kwisst blow   

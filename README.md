## **[NieR:Automata] - Glory to Mankind** 
Owned by Sam Siangchin^^

<iframe width="853" height="480" src="https://www.youtube.com/embed/mOQwMLWEJrg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## **[The distant future…]**

 Invaders from another world attack without warning, unleashing a new type of threat: weapons known as “machine lifeforms.” In the face of this insurmountable threat, mankind is driven from Earth and takes refuge on the Moon.

 The Council of Humanity organizes a resistance of android soldiers in an effort to take back their planet. To break the deadlock, the Resistance deploys a new unit of android infantry: YoRHa .

 In the forsaken wasteland below, the war between the machines and the androids rages on. A war that is soon to unveil the long-forgotten truth of this world...


## Char[a]cters

 ![2B YoRHa No. 2, Type B](https://venturebeat.com/wp-content/uploads/2017/08/nierautomata-1280-1-1488398963732_1280w.jpg?fit=750%2C422&strip=all)
                                                                                                                        
**2B (YoRHa No. 2, Type B)**

 A blade...with a quiet volition.
 
An all purpose battle android deployed as a member of the automated infantry squad, YoRHa. She is equipped with a sword for close-quarters combat, and can attack from range using the "Pod" tactical support system. Members of YoRHa forgo names and are reffered to only by their codes. Through regulations forbid them from expressing emotions, each model has its own distinguishing personality, and 2B is comparitively cool, calm, and collected.






 ![9S (YoRHa No. 9, Type S](https://www.platinumgames.com/wp-content/uploads/2016/03/9S.jpg)

 **9S (YoRHa No. 9, Type S)**

 A soul...and an ephemeral kindness.
 
Though he has the ability to attack, this YoRHa android specializes in research missions and excels in collecting information, mainly by hacking. Within YoRHa. 9S is comparitively varied in his emotional expressions and has a kind personality.



![A2 (YoRHa Type A, No. 2](https://www.platinumgames.com/wp-content/uploads/2016/03/A2-1.jpg)

**A2 (YoRHa Type A, No. 2**

 A vortex...of the past and hatred.
 
The Type A is a YoRHa prototype model that is no longer in use. She specilizes in close-range attacks. She was operated in trial basis in the process of developing official models such as 2B and 9S. Personality-wise, she has little to say and always acts independently.  



[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/bukotsunikki.svg?style=social&label=Follow%20%40bukotsunikki)](https://twitter.com/bukotsunikki)



<?php
    // Get access to $post object
    global $post;
    
    // Get twitter handle
    $twitter = get_field('twitter', 'options');
    
    // define links
    $links = array(
        'facebook' => 'https://www.facebook.com/sharer/sharer.php?u=' . get_permalink(),
        'twitter'  => 'https://twitter.com/intent/tweet?text='. get_the_title() .'&url='. get_permalink() .'&via='. $twitter,
        'mail'     => 'mailto:?subject='. get_the_title() .'&body=Take a look at this link - ' . get_permalink(),
        'linkedin' => 'https://www.linkedin.com/shareArticle?mini=true&url='. get_permalink() .'&title='. get_the_title() .'&summary=' . get_the_excerpt(),
        'gplus'    => 'https://plus.google.com/share?url=' . get_permalink()
    );
?>

<nav class="share" role="menu" aria-label="Share Links">
    <li class="share__item">
        <a href="<?php echo $links['facebook']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-fb"></span><span class="is-hidden">Share this Post on Facebook</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['twitter']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-tw"></span><span class="is-hidden">Share this Post on Twitter</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['mail']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-mail"></span><span class="is-hidden">Share this Post via Email</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['linkedin']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-li"></span><span class="is-hidden">Share this Post on Linked In</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['gplus']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-gp"></span><span class="is-hidden">Share this Post on Google Plus</span></a>
    </li>
</nav>









    
  
  
  
  
  
  
  
  
  
 [Check out Sir Gain's Github Page](https://641n.github.io/)

 Sam was here

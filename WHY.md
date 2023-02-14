---
layout: default
nav_order: 2
---

## Why Transition / Transmaxx

> Do not let anyone gatekeep you from transitioning
You may be in doubt and thus ask people close to you or a gender clinic "should you transition/ are you
allowed" - this is not a good idea.
>
> It's very unlikely anyone close to you has a proper understanding of the consequences that come with 
transitioning, what the pros and cons will be for you. If your family of origin is transphobic just 
boymode and leave, you don't need them in your life if they become a negative for you.
>
> You have the right to rule over your own body, do not let any doctor or parent take that right away from
you. If you cannot get an official prescription in time just order online it's actually rather cheap. DIY
HRT can be safer and more effective that official prescription

{: .highlight }
> :heavy_check_mark: Transitioning might improve this
>
> :x: Transitioning might not improve this / negatively affects

<details>
<summary><b><font size="+1">Physical Characteristics</font></b></summary>

{% for reason in site.data.physical -%}
    :heavy_check_mark: {{ reason.positive }} 
    <br>
    :x: {{ reason.negative }}
    <br><br>
{%- endfor -%}

</details>


<details>
<summary><b><font size="+1">Mental Characteristics</font></b></summary>

{% for reason in site.data.mental -%}
    :heavy_check_mark: {{ reason.positive }} 
    <br>
    :x: {{ reason.negative }}
    <br><br>
{%- endfor -%}

</details>

<details>
<summary><b><font size="+1">Social Characteristics</font></b></summary>

{% for reason in site.data.social -%}
    :heavy_check_mark: {{ reason.positive }} 
    <br>
    :x: {{ reason.negative }}
    <br><br>
{%- endfor -%}

</details>

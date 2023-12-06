# css multiple column

> ## column-count

> ## column-gap

> ## column-rule-style

> ## column-rule-width

> ## column-rule-color

> ## column-rule

> ## column-span

> ## column-width

## Example 

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{ margin: 0; box-sizing: border-box;}
        body{
            background-image: url(image/bg.jpg);
            background-size: 50%;
            background-repeat: no-repeat;
        }
        .news{ 
            padding: 2%;
            background-color: rgba(0,0,0,0.30); 
            border: 1px solid black;
            text-align: justify;
            color: white;
            font-size: 18px;
            /* case 1 */
            /* column-count: 4; */
            column-gap: 40px;
            column-rule-style: dashed;
            column-rule-color: royalblue;
            column-rule-width: 2px;
            column-rule: 5px solid tomato;
            /* case 2 */
            column-width: 250px;
        }
        h1{ column-span: all; padding: 2%; background-color: rgba(255, 215, 0,0.30);} 
        img{ width: 100%; height: 40vh; display: block; column-span: all; margin-top: 2vh;}
    </style>
</head>
<body>
    <div class="news">
        
        <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse, iusto.</h1>


       
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis minus doloribus maxime eos ratione beatae voluptates excepturi quod deleniti! A debitis voluptatibus quae sit eius qui labore fuga dignissimos accusantium illum inventore maiores error facilis laudantium, temporibus quas possimus beatae omnis ex vitae accusamus culpa, autem, eligendi quibusdam! Corrupti harum explicabo eos perferendis eum mollitia, eligendi quod reprehenderit nobis non ea minus impedit nam itaque numquam fuga officiis debitis, molestiae perspiciatis illo repudiandae inventore quaerat dolorem! Cumque aliquam doloremque nemo, eum explicabo qui natus maxime eligendi dolor dignissimos impedit veritatis exercitationem nisi, at reiciendis iusto ratione repellat culpa voluptas corporis tempore beatae officiis vel excepturi? Rem dolorum eveniet maxime tempore fugit quaerat repellat, doloremque distinctio, explicabo mollitia quod natus vero architecto ex at. Rem saepe cumque eaque maxime placeat aliquam enim voluptate earum? Dolorum dolore iure repellat, placeat labore excepturi sint assumenda dolorem, quasi aliquid laboriosam corrupti veritatis modi omnis doloribus unde ut possimus blanditiis quia at consequatur cum quaerat. Cupiditate, quam! Blanditiis dolorum autem alias placeat, quod facilis ea aut, perferendis eius accusantium, officiis optio veniam illum beatae! Nemo non eum sunt optio aspernatur expedita ea aut quidem ipsa repellendus! Deleniti alias, rerum iure velit ab dolorum voluptatibus, vero pariatur incidunt saepe cupiditate distinctio vel repellendus, explicabo ipsam maxime consequatur voluptate cum nihil praesentium ducimus reiciendis nemo blanditiis? Omnis mollitia, expedita exercitationem ipsam soluta eos tempora sint! Nulla eaque cumque quo neque, tempora, molestias, vel totam natus in amet sequi non eveniet repellendus. Magni dignissimos qui nemo, illum saepe assumenda quos itaque modi maiores corrupti, libero quibusdam? Quod enim necessitatibus id sit. Praesentium excepturi, error corrupti esse ullam rem enim! Explicabo odit eos voluptas? Obcaecati, minus. Quod possimus fugiat nesciunt sit deleniti tenetur minima. Rem asperiores at enim reiciendis illo praesentium assumenda blanditiis, voluptas nesciunt nam repellat mollitia quisquam ex, perferendis commodi soluta iste architecto laborum tempore ipsum aliquam sunt sed. Doloremque asperiores consectetur omnis quas doloribus? Maxime officia, nostrum perspiciatis magnam, recusandae cupiditate laudantium eaque provident minima sed commodi explicabo soluta neque ea optio natus, id molestias sint tempore repellendus! Laborum dolore nostrum repellendus reprehenderit iure totam ipsam ab rerum quae dicta id obcaecati sunt rem, provident sequi delectus accusamus modi. Consequuntur quod enim numquam tempora perspiciatis cupiditate maxime dolor commodi earum inventore! Excepturi eius sed earum, provident, doloremque quidem a mollitia corrupti expedita porro doloribus nobis hic iste nam, veniam consequuntur? Aliquid eaque corporis error dolor sunt saepe voluptatibus, amet maxime libero. Beatae, consequuntur! Repellat perferendis recusandae cum quia culpa enim obcaecati laboriosam, nam totam doloremque corporis natus dolore nostrum numquam necessitatibus laudantium officia, sint, ducimus voluptate architecto quae quas alias in. Perspiciatis facilis autem aut reprehenderit harum et sint tenetur, necessitatibus quasi dolorum accusamus dolores deleniti adipisci natus aliquid eligendi. Sequi ab dolorum explicabo in necessitatibus odio deserunt excepturi autem nisi sit veniam, magnam ea itaque numquam, architecto error tempore omnis iste voluptates. Natus fuga eaque, vitae consectetur labore eos ab nesciunt molestias? Fugiat consequuntur voluptatem aspernatur sapiente fugit ex temporibus quos corporis ab! Voluptatem neque sint inventore. Obcaecati veritatis sit illo placeat inventore id consequatur eos dolorem tempora incidunt voluptas vero sunt alias sed, cupiditate quisquam expedita, eligendi rerum laboriosam explicabo ducimus. Nesciunt suscipit nulla atque rem eos repellat, vel provident officiis adipisci. Soluta aliquid deleniti cumque, fuga fugit animi quos quidem hic quis, vero minus. Natus, ullam enim accusantium ad facilis aliquid consequuntur illo cupiditate nesciunt delectus, quod rerum possimus iusto sunt commodi aliquam architecto ex perferendis alias dolorem eveniet ea praesentium molestiae sint. Nulla totam aut soluta aliquam, nostrum unde voluptate reiciendis provident, cumque amet sed officia doloribus doloremque impedit maiores numquam voluptas.
        <!-- <img src="image/banner1.jpg" alt="banner"> -->
    </div>
    
</body>
</html>
```

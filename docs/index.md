doctype html

html

  head

    title Mohit Kaushik | mohitkaushik.com

    block scripts

    block style

        link(rel="stylesheet", href="../static/base.css")

  body

    nav#navbar

        div#logo

            ul 

              li

                a(href='/')

                  img(src='/static/img/logo.png')

              li

                a(href='/') Mohit

        div#option

            ul

                li #[a(href="/") Home]

                li #[a(href="/resume") Resume]

                li #[a(href="/blog") Blog]

                li #[a(href="/contact") Contact]

    block content

    block foot

      #footer

        div#fikon

          ul

            li

              a(href='https://in.linkedin.com/in/mohit-kaushik-a48357188?trk=public_profile_browsemap')

                img(src='/static/img/f1.png')

            li

              a(href='https://www.facebook.com/mohit.kaushik.98434')

                img(src='/static/img/f2.png')    

            li

              a(href='https://www.instagram.com/_mohit_kaushik__/')

                img(src='/static/img/f3.png')  

            li

              a(href='https://github.com/kaushikmt157')

                img(src='/static/img/f4.png')

            li

              a(href='https://twitter.com/MohitKa98165113')

                img(src='/static/img/f5.png')

        marquee(direction='left') copyright &copy; mohitkaushik.com | All Rights Reserved

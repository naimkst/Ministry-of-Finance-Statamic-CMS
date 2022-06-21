---
id: home
blueprint: home
title: الرئيسية
template: home
home:
  -
    type: set
    attrs:
      values:
        type: hero_section
        hero_slider:
          -
            slider_title: 'أهلا بكم في موقع وزارة المالية - دولة فلسطين'
            slider_image: images/hero-image.jpg
            type: add_slider
            enabled: true
          -
            slider_title: 'Welcome to the website of the ministry of finance - State of Palestine'
            slider_image: images/tab-image.jpg
            type: add_slider
            enabled: true
          -
            slider_title: 'Welcome to the website of the ministry of finance - State of Palestine'
            slider_image: images/single-news-image.jpg
            type: add_slider
            enabled: true
  -
    type: set
    attrs:
      values:
        type: service_slider
        service_slider_item:
          -
            service_title: 'General Budget'
            service_page_link: '#'
            flat_icon_class: flaticon-briefcase
            type: add_service
            enabled: true
            icon: images/briefcase.png
            hover_icon: images/briefcase-white.png
          -
            service_title: 'Ministry of Finance'
            service_page_link: '#'
            flat_icon_class: flaticon-parthenon
            type: add_service
            enabled: true
            icon: images/parthenon.png
            hover_icon: images/parthenon-white.png
          -
            service_title: 'E- Services'
            flat_icon_class: 'fas fa-bus-alt'
            type: add_service
            enabled: true
            icon: images/school-bus.png
            hover_icon: images/school-bus-white.png
          -
            service_title: 'public administrations'
            service_page_link: '#'
            icon: images/factory.png
            hover_icon: images/factory-white.png
            type: add_service
            enabled: true
  -
    type: set
    attrs:
      values:
        type: news_area
        news_title: 'أخبار وميديا'
        news_slug: 'The latest news and press coverage of the Ministry''s activities'
        news_archive_button_text: 'أرشيف الأخبار'
        news_button_link: '#'
  -
    type: set
    attrs:
      values:
        type: department_section
        department_title: 'الإدارات العامة'
        department_button_text: 'عرض المزيد'
        department_link: 'entry::9dff5c54-313b-4085-80e4-184dec0fcb25'
  -
    type: set
    attrs:
      values:
        type: e_service
        e_service_title: 'الخدمات الالكترونية'
        e-services_slug: 'Electronic services provided by the Ministry of Finance in cooperation with various departments'
        e-service_limit: 6
  -
    type: set
    attrs:
      values:
        type: counter_section
        counter_item:
          -
            icon: images/bridge.png
            title: 'Total Disability'
            counter_number: 6
            percentage_or_million: '%'
            type: add_counter
            enabled: true
          -
            icon: images/nature.png
            title: 'Public Debt'
            counter_number: 32
            percentage_or_million: '%'
            type: add_counter
            enabled: true
          -
            icon: images/directions.png
            title: 'Total Expenses'
            counter_number: 5
            percentage_or_million: ' Million'
            type: add_counter
            enabled: true
          -
            icon: images/004-jogging.png
            title: 'Total Revenue'
            counter_number: 62
            percentage_or_million: ' Million'
            type: add_counter
            enabled: true
  -
    type: paragraph
updated_by: 00dab2f0-a935-4acf-99ab-161b5e8bd365
updated_at: 1655797624
---
Welcome to your new Statamic website.

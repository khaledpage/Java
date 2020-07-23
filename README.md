# Java
LocalDate
        LocalDate d= LocalDate.of(2020,1,1);
        LocalDate d2= LocalDate.of(2021,1,1);
        d.isAfter(d2);
        LocalDate today = LocalDate.now();
        String formattedDate = today.format(DateTimeFormatter.ofPattern("dd.MM.yy"));
        System.out.println(formattedDate);
        System.out.println(d.isAfter(d2));

for the attend page
req:store ppl in study room. a page to show who is in studyroom, and show how long they hv stored
    if  higher than 6, highlight and give coupon, set coupon evry six plus one, 

design: batch processing
        use three table (id as primary key)
        one store ppl in studyroom
        one store and ppl time for each
        one store the coupon and total time

        html, two page, one show who in room (pyc net)(refresh)
        one show total, set rank

        js, link with the rfid, link sch database, update supabase
            cal the time, add function refresh, six half hour cut, invalid input when 1830-0815

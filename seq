def color_text(text, color_code):
    return f"\033[{color_code}m{text}\033[90m"

while True:
    sequence = input("Please enter the sequence as a block of text without commas: ")
 
    ABC_count = sequence.count("ABC")
    abc_count = sequence.count("abc")
    BCA_count = sequence.count("BCA")
    bca_count = sequence.count("bca")
    CAB_count = sequence.count("CAB")
    cab_count = sequence.count("cab")
    CBA_count = sequence.count("CBA")
    cba_count = sequence.count("cba")
    ACB_count = sequence.count("ACB")
    acb_count = sequence.count("acb")
    BAC_count = sequence.count("BAC")
    bac_count = sequence.count("bac")

    successful_alterations = (ABC_count + BCA_count + CAB_count + CBA_count + ACB_count + BAC_count + abc_count + bca_count + cab_count + cba_count + acb_count + bac_count)
    total_entries = len(sequence)
    total_alterations = total_entries - 2
    percentage_successful = (successful_alterations / total_alterations) * 100
     
    print(color_text("Your total number of entries is:", 91), total_entries)
    print(color_text("Your total number of alterations is:", 93), total_alterations)
    print(color_text("Your number of successful alterations is:", 92), successful_alterations)
    print(color_text("Your percentage of successful alterations is:", 94), percentage_successful)
    
    welcome=input("Press the enter key if you would like to enter another sequence. If not type no: ")
    if welcome.lower() == "no":
        break
    
print(color_text("Thank you for using this program!",36))
input(color_text("\n\nPress the enter key to exit", 36))

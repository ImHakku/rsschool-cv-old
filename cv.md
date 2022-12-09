Oleg Lipinskiy
Kontacts
Location: Mykolaiv, Ukraine
Phone: +380-99-368-39-61
Email: lipinskii97@gmail.com
Telegham: @im_hakku
Discord rs-school: Hakku (@Imhakku)
GitHub: [ImHakku](https://github.com/ImHakku)
About Me
I am now at the beginning of my journey of learning programming and web development. I am currently engaged in self-education at the rs-school course. Wish me good luck )
Skills
Basic HTML/CSS/Git/C
Code Example
void selection_sort(int array[], int array_size)
{
    for (int i = 0; i < array_size; i++) {
        int smallest_element = i;
        bool found_smallest = false;
        for (int j = i + 1; j < array_size; j++) {
            if (array[j] < array[smallest_element]) {
                smallest_element = j;
                found_smallest = true;
            }
        }
        if (found_smallest) {
            int tmp = array[i];
            array[i] = array[smallest_element];
            array[smallest_element] = tmp;
            found_smallest = false;
        }
    }
    return;
}
Experience
Education
University: Admiral Makarov National University of Shipbuilding, Information management systems and technologies 
Courses:
CS50
RS-school
English:
Pre-Intermediate
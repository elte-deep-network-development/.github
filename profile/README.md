
# Deep Network Development Course

Welcome to the **Deep Network Development** course! 📚 This repository is structured to help teachers iterate on course materials, assignments, and practice code in an organized, collaborative environment. 

Each topic is divided into a separate repository, allowing easy access and management of content.

## Repository Structure

Each repository corresponds to a specific topic in the class. The repositories are structured to support continuous iteration on teaching materials:

- **Branches are divided by semesters**: For example, `2024/25/1` refers to the first semester of the `2024/25` academic year.
- The **main branch mirrors the latest semester**, providing a base for updating and iterating on materials.
- **Previous semester branches are locked** and remain read-only for reference, ensuring historical documentation of course material.
- Each semester has a separate `Practice` and `Lecture` directory.

## Working with Course Material

To revise and improve upon the course content, follow these steps:

1. **Clone the repository**:
   - Use one of the following methods:
     - **SSH**: `git clone git@github.com:your-org/repo-name.git`
     - **HTTPS**: `git clone https://github.com/your-org/repo-name.git`
     - **GitHub CLI**: `gh repo clone your-org/repo-name`

2. **Create a new branch for the current semester**:
   ```bash
   git checkout -b 2024/25/1
   ```
   This new branch will be used to update or iterate on the existing course material for the ongoing semester.

3. **Push your branch to GitHub**:
   ```bash
   git push --set-upstream origin 2024/25/1
   ```

4. **Iterate on the course material**: As you make changes to lectures, assignments, or practice code, ensure that:
   - All materials are up-to-date and relevant for the current semester.
   - Documentation is maintained in the `README.md` file.
   - Bugs, improvements, or key details are tracked in the GitHub Wiki.

## Merging Your Branch at the End of the Semester

At the end of the semester, once the course material has been finalized, follow these steps to merge your branch into the main branch:

1. **Ensure your branch is up to date** with the main branch:
   ```bash
   git checkout main
   git pull origin main
   ```

2. **Resolve any merge conflicts** if they arise. Ensure all conflicts are resolved before proceeding.

3. **Merge your branch into the main branch**:
   ```bash
   git merge 2024/25/1
   ```

4. **Push the updated main branch to GitHub**:
   ```bash
   git push origin main
   ```

This process ensures that your revisions and updates to the course material are reflected in the main branch and documented for future use.

## Slides

Each slides follows a rigid Slide Master format to ensure standardization. For modifying the slides, please use one of the predefined layouts!

## Responsibilities

As a teacher or a demonstrator, you are responsible for maintaining and iterating on the course content. This includes:

- **Documentation**: Keeping the `README.md` updated with changes to the course material, assignment instructions, or practical examples.
- **Tracking Changes**: Use the GitHub Wiki to log key changes, known issues, or important details about the course.
- **Collaborating with Other Teachers and Demonstrators**: Each topic repository is shared among teachers and current demonstrators, allowing collaboration while ensuring that historical course versions are preserved.

## Final Notes

This organizational structure ensures that all course material is easily accessible, up-to-date, and documented for future use. By following this workflow, you'll be able to efficiently iterate on lectures, assignments, and other resources.

If any issues arise with GitHub, Git, or the Organization, contact me at [imremolnar@inf.elte.hu](mailto:imremolnar@inf.elte.hu).

Happy teaching! 🎓

# TODO 2025/26/1

Lecture:
- Add Transformers part 2 (DeepSeek)
- Add BEiT, Swin2, LeVit to vision transformers, add DINO
  
Practice:
- Transformers part 2: NMT with Transformers, GPT2 - Andrej Karpathy
- Deep Learning Tools part 2: Neural Image Rendering, Generative Modeling

Additional:
- .ipynb similarity checker code
- Homework redistribution code

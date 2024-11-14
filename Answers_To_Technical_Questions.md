Q-How long did you spend on the coding test?
Ans-Overall it took me 7-8 hours to complete the coding test.

Q-What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.


One of the most useful features added in the latest version of React (React 18) is automatic batching of updates. This allows multiple state updates to be batched together, reducing unnecessary re-renders and improving performance.

Here’s a simple example demonstrating automatic batching in a manager app:

const UpcomingTasks = () => {
  const [upcomingTasks, setUpcomingTasks] = useState([]);
  const [allTasks, setAllTasks] = useState([]);
  const [filteredTasks, setFilteredTasks] = useState([]);

  useEffect(() => {
    const storedTasks = JSON.parse(localStorage.getItem('tasks')) || [];
    const upcoming = storedTasks.filter((task) => task.status === 'Upcoming');
    setAllTasks(storedTasks);
    setUpcomingTasks(upcoming);
    setFilteredTasks(upcoming); // Initialize with all upcoming tasks
  }, [allTasks]);

...//
} 

In this example, i used upcomingTasks allTasks and FilteredTasks, all updates in a single render, making the app more efficient.





Q-How would you track down a performance issue in production? Have you ever had to do this?
Optimize Queries: If dealing with a large dataset (like 10000+ tasks), Performing operation on that data will get complex(such as search ).





Q-If you had more time, what additional features or improvements would you consider adding to the task management application?
Ans-Below are some additional features that i would consider adding to the application-
**Authentication**: Allow users to log in and save tasks to a personal account.
**Task Reminders**: Send notifications for tasks nearing their due dates.
**Dark Mode**: Add a dark mode option for better user experience at night.